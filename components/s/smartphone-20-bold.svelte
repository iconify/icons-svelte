<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkuaw6bpa.css';
import '../../css/e/e1qe98bwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rkuaw6bpa"/><path class="e1qe98bwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smartphone-20-bold" {...props}></Icon>
