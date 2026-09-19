<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc6qyrb-v.css';
import '../../css/q/qrq26sblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cc6qyrb-v"/><path class="qrq26sblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:unsaved" {...props}></Icon>
