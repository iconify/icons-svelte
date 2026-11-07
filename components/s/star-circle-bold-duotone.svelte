<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpv5vhdla.css';
import '../../css/n/ngqnwkb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpv5vhdla"/><path class="ngqnwkb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-circle-bold-duotone" {...props}></Icon>
