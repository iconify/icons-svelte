<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjb570f_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjb570f_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:shopping-cart-add-01" {...props}></Icon>
