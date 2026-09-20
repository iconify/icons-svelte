<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/r/ryp3spl8y.css';
import '../../css/i/ivbuyeg9r.css';
import '../../css/c/czbbm17fv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ryp3spl8y"/><path class="ivbuyeg9r"/><path class="czbbm17fv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:shopping-cart-sharp-two-tone" {...props}></Icon>
