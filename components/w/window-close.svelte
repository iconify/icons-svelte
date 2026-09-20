<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0m-qub2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0m-qub2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:window-close" {...props}></Icon>
