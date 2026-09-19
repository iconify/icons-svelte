<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rihgeqb4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rihgeqb4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:soil-moisture-field" {...props}></Icon>
