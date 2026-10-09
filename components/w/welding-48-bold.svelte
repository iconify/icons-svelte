<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg-g_cb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rg-g_cb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:welding-48-bold" {...props}></Icon>
