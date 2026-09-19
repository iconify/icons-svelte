<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydda9xosv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydda9xosv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:shopping-cart-solid" {...props}></Icon>
