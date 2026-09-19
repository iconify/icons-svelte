<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxm3opmuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="nxm3opmuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:undo" {...props}></Icon>
