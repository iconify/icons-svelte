<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix_lw37hq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ix_lw37hq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shopping-cart-48-bold" {...props}></Icon>
