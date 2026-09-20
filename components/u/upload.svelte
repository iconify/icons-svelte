<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy8533erf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zy8533erf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:upload" {...props}></Icon>
