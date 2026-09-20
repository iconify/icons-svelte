<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-w5j8bdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-w5j8bdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:shopping-cart-download" {...props}></Icon>
