<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej1v3t0wm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ej1v3t0wm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:water-tap-with-droplet" {...props}></Icon>
