<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy3_k6b3r.css';
import '../../css/z/z-jza3xhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vy3_k6b3r"/><path class="z-jza3xhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:screen-smartphone" {...props}></Icon>
