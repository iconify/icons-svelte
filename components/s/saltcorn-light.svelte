<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc_npxm2i.css';
import '../../css/n/nz0jllbgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mc_npxm2i"/><path class="nz0jllbgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:saltcorn-light" {...props}></Icon>
