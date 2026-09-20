<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxb7hz46y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pxb7hz46y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:screen-filled" {...props}></Icon>
