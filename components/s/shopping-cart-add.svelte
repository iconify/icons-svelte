<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0y8ghj5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0y8ghj5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:shopping-cart-add" {...props}></Icon>
