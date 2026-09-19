<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht-g1lbxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":456};
const content = `<path class="ht-g1lbxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:shopping-cart-add" {...props}></Icon>
