<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rizmdybhn.css';
import '../../css/v/vfm45qp2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rizmdybhn"/><path class="vfm45qp2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:scalpel-select" {...props}></Icon>
