<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1ur40y3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m1ur40y3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:shopping-cart-solid" {...props}></Icon>
