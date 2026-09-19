<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cik39oe1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cik39oe1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:wind-power" {...props}></Icon>
