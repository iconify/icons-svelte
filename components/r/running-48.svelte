<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4s6aob2m.css';
import '../../css/n/n0xyitehn.css';
import '../../css/w/w3e274hyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s4s6aob2m"/><path class="n0xyitehn"/><path class="w3e274hyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:running-48" {...props}></Icon>
