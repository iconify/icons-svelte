<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb1jambhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="nb1jambhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:shopping-cart-plus-light" {...props}></Icon>
