<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfc4w3bvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfc4w3bvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shopping-cart-2-line" {...props}></Icon>
