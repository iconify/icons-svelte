<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0rev_bok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="i0rev_bok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shopping-bag-hand-bag-2-shopping-bag-purse-goods-item-products" {...props}></Icon>
