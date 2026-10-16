<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2gs_oovh.css';
import '../../css/r/rme-dq93w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z2gs_oovh"/><path class="rme-dq93w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scroll-20-bold" {...props}></Icon>
