<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flb3ulx1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="flb3ulx1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:victorialogs-dark" {...props}></Icon>
