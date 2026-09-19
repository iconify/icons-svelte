<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0v0s9b_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s0v0s9b_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-footnote" {...props}></Icon>
