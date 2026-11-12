<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jelsw2bbk.css';
import '../../css/p/phs9k_bln.css';
import '../../css/t/tjav81vfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jelsw2bbk"/><path class="phs9k_bln"/><path class="tjav81vfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:streamyfin-dark" {...props}></Icon>
