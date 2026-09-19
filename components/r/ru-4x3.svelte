<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbsiz1bro.css';
import '../../css/r/rt2t23vus.css';
import '../../css/m/mav5s0-rh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="fbsiz1bro"/><path class="rt2t23vus"/><path class="mav5s0-rh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:ru-4x3" {...props}></Icon>
