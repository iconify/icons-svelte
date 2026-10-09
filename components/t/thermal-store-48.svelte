<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlgr2s59b.css';
import '../../css/s/s1z91sb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xlgr2s59b"/><path class="s1z91sb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermal-store-48" {...props}></Icon>
