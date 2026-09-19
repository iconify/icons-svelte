<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9zy8wb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":368,"height":384};
const content = `<path class="x9zy8wb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:wrap-text" {...props}></Icon>
