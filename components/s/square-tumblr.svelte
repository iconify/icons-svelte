<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xov3r3xqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="xov3r3xqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:square-tumblr" {...props}></Icon>
