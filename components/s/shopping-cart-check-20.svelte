<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3h3u0bwn.css';
import '../../css/p/puz5jibvr.css';
import '../../css/q/q9z_cedxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g3h3u0bwn"/><path class="puz5jibvr"/><path class="q9z_cedxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shopping-cart-check-20" {...props}></Icon>
