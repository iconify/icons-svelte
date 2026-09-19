<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypg_y81bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ypg_y81bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:shopping-cart-fill-12" {...props}></Icon>
