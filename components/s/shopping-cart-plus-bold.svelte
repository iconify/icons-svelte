<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsclkac7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="rsclkac7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:shopping-cart-plus-bold" {...props}></Icon>
