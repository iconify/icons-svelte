<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlgq87u_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nlgq87u_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:sun" {...props}></Icon>
