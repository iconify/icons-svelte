<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xph1b26-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xph1b26-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wifi-low-48-bold" {...props}></Icon>
