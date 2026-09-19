<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5zcy4b-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w5zcy4b-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:shopping-cart-20-solid" {...props}></Icon>
