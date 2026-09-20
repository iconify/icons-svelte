<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvg_0h2iy.css';
import '../../css/b/b8e-k_44m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xvg_0h2iy"/><path class="b8e-k_44m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:xplicittrust" {...props}></Icon>
