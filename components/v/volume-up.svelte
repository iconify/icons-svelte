<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j35eaocdf.css';
import '../../css/d/d3ppxtb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j35eaocdf"/><path class="d3ppxtb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:volume-up" {...props}></Icon>
