<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdbl3bnfw.css';
import '../../css/e/e2li34b1z.css';
import '../../css/x/xh-rjd76x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":16};
const content = `<path class="zdbl3bnfw"/><path class="e2li34b1z"/><path class="xh-rjd76x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:textarea" {...props}></Icon>
