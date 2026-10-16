<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj6zr-b_t.css';
import '../../css/z/zt2hc146k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nj6zr-b_t"/><path class="zt2hc146k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:storage-heater-48-bold" {...props}></Icon>
