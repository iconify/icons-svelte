<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk274hgmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nk274hgmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wallmounted-surveillance-camera" {...props}></Icon>
