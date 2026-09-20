<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk0phibge.css';
import '../../css/e/e95vgl-bz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rk0phibge"/><path class="e95vgl-bz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:synclyrics-dark" {...props}></Icon>
