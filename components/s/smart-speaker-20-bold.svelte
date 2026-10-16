<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi4epefpx.css';
import '../../css/o/oiwmoi7co.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pi4epefpx"/><path class="oiwmoi7co"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-speaker-20-bold" {...props}></Icon>
