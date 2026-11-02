<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mydz6fg-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mydz6fg-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shopping-cart-2-fill" {...props}></Icon>
