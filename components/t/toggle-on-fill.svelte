<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxp_3lb6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vxp_3lb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:toggle-on-fill" {...props}></Icon>
