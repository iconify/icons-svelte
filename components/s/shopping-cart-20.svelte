<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl3m84wvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kl3m84wvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shopping-cart-20" {...props}></Icon>
