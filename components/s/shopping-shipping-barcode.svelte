<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in_8m6pkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="in_8m6pkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:shopping-shipping-barcode" {...props}></Icon>
