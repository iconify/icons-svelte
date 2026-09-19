<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlc03bcgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nlc03bcgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:shopping-cart-fill-16" {...props}></Icon>
