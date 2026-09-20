<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhl8kcbfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fhl8kcbfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:trending-flat" {...props}></Icon>
