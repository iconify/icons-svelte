<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxe0xlbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mxe0xlbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:solar-panel" {...props}></Icon>
