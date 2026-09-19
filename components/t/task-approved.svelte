<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb7z8wwtr.css';
import '../../css/r/rututhb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sb7z8wwtr"/><path class="rututhb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:task-approved" {...props}></Icon>
