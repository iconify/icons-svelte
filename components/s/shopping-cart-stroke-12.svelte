<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-mdt4b_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="y-mdt4b_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:shopping-cart-stroke-12" {...props}></Icon>
