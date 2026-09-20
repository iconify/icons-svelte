<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1-j1r2ty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="u1-j1r2ty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shopping-store-1-store-shop-shops-stores" {...props}></Icon>
