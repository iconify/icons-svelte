<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib-vq554x.css';
import '../../css/a/aqsnv9bnd.css';
import '../../css/s/sh06c0bcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ib-vq554x"/><path class="aqsnv9bnd"/><path class="sh06c0bcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shopping-cart-check-20-bold" {...props}></Icon>
