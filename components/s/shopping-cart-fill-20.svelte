<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2xs_abqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e2xs_abqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:shopping-cart-fill-20" {...props}></Icon>
