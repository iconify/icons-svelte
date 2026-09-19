<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aycs3t8th.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="aycs3t8th"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:shopping-cart-solid" {...props}></Icon>
