<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um28xnbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="um28xnbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:shopping-shipping-discount-coupon" {...props}></Icon>
