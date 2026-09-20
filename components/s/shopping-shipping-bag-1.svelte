<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdcu93bzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zdcu93bzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:shopping-shipping-bag-1" {...props}></Icon>
