<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p23qzib1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p23qzib1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:xvg" {...props}></Icon>
