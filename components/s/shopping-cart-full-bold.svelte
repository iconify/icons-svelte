<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpm6mobiy.css';
import '../../css/c/cuklhhb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpm6mobiy"/><path class="cuklhhb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:shopping-cart-full-bold" {...props}></Icon>
