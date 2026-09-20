<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnbbg7bgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wnbbg7bgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:symbol" {...props}></Icon>
