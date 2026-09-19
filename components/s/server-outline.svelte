<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mud1l5kug.css';
import '../../css/t/tjyxhabsq.css';
import '../../css/c/crqj_mbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="mud1l5kug"/><path class="tjyxhabsq"/><path class="crqj_mbjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:server-outline" {...props}></Icon>
