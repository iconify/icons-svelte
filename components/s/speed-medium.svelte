<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr977ni_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vr977ni_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:speed-medium" {...props}></Icon>
