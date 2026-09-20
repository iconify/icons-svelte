<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i41kp_bfp.css';
import '../../css/z/z8wncuzib.css';
import '../../css/j/jo99vqg6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i41kp_bfp"/><path class="z8wncuzib"/><path class="jo99vqg6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:video-movies-square-off" {...props}></Icon>
