<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pia1jk4qr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pia1jk4qr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:shipment-delivery" {...props}></Icon>
