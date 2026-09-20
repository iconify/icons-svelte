<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx4otwbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cx4otwbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shopping-cart-line" {...props}></Icon>
