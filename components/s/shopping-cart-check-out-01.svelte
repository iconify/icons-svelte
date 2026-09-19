<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxp457pzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxp457pzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:shopping-cart-check-out-01" {...props}></Icon>
