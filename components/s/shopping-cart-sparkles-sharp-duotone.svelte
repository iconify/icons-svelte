<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/v/vt6hcub9p.css';
import '../../css/z/zgknwabmn.css';
import '../../css/k/kvwkwfbtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vt6hcub9p"/><path class="zgknwabmn"/><path class="kvwkwfbtt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:shopping-cart-sparkles-sharp-duotone" {...props}></Icon>
