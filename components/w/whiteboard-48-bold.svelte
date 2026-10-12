<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx1t0xbct.css';
import '../../css/u/u899ipb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kx1t0xbct"/><path class="u899ipb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:whiteboard-48-bold" {...props}></Icon>
