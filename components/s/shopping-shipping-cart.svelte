<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3x4aha0j.css';
import '../../css/t/tjjdtrb6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l3x4aha0j"/><path class="tjjdtrb6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:shopping-shipping-cart" {...props}></Icon>
