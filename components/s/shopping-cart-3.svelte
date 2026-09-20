<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7s5u-sdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="u7s5u-sdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shopping-cart-3" {...props}></Icon>
