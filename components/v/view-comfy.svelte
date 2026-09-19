<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1zlj_b8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":384};
const content = `<path class="k1zlj_b8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:view-comfy" {...props}></Icon>
