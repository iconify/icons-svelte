<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgvbcfb3d.css';
import '../../css/x/x_in5db1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vgvbcfb3d"/><path class="x_in5db1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tinfoil-light" {...props}></Icon>
