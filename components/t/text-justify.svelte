<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_w9rbcxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u_w9rbcxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:text-justify" {...props}></Icon>
