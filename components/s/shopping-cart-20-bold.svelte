<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/faxxu_v1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="faxxu_v1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shopping-cart-20-bold" {...props}></Icon>
