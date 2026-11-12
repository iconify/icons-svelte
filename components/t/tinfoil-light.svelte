<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgvbcfb3d.css';
import '../../css/i/i-jh_sbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vgvbcfb3d"/><path class="i-jh_sbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tinfoil-light" {...props}></Icon>
