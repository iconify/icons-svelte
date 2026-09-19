<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po_ex1brd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="po_ex1brd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:succession-flow-connection" {...props}></Icon>
