<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp3zy8coe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yp3zy8coe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:triangle-arrow-reload-horizontal-1-remix" {...props}></Icon>
