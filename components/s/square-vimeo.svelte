<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdt0mx1ju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="fdt0mx1ju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:square-vimeo" {...props}></Icon>
