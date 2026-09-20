<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-saaebsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="h-saaebsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:tree-coniferous-14" {...props}></Icon>
