<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkq3vx3ve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkq3vx3ve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shopping-cart-1-fill" {...props}></Icon>
