<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y74afh5ul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y74afh5ul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:shopping-cart-stroke-16" {...props}></Icon>
