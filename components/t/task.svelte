<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g11mse5ac.css';
import '../../css/p/pfm1z1-ik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g11mse5ac"/><path class="pfm1z1-ik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:task" {...props}></Icon>
