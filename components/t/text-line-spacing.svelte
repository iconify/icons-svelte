<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f43zlbc0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f43zlbc0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-line-spacing" {...props}></Icon>
