<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfool6bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="bfool6bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shopping-cart-basket-3-shopping-basket" {...props}></Icon>
