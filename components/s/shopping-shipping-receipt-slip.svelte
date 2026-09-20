<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtevuubjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qtevuubjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:shopping-shipping-receipt-slip" {...props}></Icon>
