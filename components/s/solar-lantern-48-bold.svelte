<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3g_hqbet.css';
import '../../css/m/mhuifpbqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e3g_hqbet"/><path class="mhuifpbqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-lantern-48-bold" {...props}></Icon>
