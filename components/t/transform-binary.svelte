<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7ik_xtrn.css';
import '../../css/w/wx-066bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e7ik_xtrn"/><path class="wx-066bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:transform-binary" {...props}></Icon>
