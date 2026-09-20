<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/faydqub3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="faydqub3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shopping-cart-arrow-right" {...props}></Icon>
