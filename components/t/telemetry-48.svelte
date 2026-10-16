<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl9bja3bz.css';
import '../../css/r/rp0ywbdoi.css';
import '../../css/f/f99glvbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cl9bja3bz"/><path class="rp0ywbdoi"/><path class="f99glvbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:telemetry-48" {...props}></Icon>
