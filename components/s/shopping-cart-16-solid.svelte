<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqunbxb7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rqunbxb7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:shopping-cart-16-solid" {...props}></Icon>
