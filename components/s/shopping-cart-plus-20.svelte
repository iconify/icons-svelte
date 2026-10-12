<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3h3u0bwn.css';
import '../../css/p/puz5jibvr.css';
import '../../css/y/y4i3220kc.css';
import '../../css/z/zkdyo_ief.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g3h3u0bwn"/><path class="puz5jibvr"/><path class="y4i3220kc"/><path class="zkdyo_ief"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shopping-cart-plus-20" {...props}></Icon>
