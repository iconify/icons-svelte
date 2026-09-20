<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5tt7bcjs.css';
import '../../css/v/vxt0-sbfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f5tt7bcjs"/><path class="vxt0-sbfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:shopping-shipping-shipment-deliver" {...props}></Icon>
