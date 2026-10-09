<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj6w8j6-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rj6w8j6-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shopping-cart-48" {...props}></Icon>
