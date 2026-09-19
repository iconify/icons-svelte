<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz_vbibin.css';
import '../../css/x/xb-o3nqnz.css';
import '../../css/u/u_ozfpbev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="qz_vbibin"/><path class="xb-o3nqnz"/><path class="u_ozfpbev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:wallet-outline" {...props}></Icon>
