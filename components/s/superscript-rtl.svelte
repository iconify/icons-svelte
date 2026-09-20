<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvi_qzbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cvi_qzbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:superscript-rtl" {...props}></Icon>
