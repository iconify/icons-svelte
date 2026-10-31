<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp_01h4ee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lp_01h4ee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shopping-cart-fill-round" {...props}></Icon>
