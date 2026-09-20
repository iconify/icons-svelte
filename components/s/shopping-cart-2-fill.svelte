<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0e90mbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v0e90mbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shopping-cart-2-fill" {...props}></Icon>
