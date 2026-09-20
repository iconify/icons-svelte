<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e328_0bet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e328_0bet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shopping-cart-fill" {...props}></Icon>
