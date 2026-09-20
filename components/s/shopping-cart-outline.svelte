<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tny0wxbmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tny0wxbmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:shopping-cart-outline" {...props}></Icon>
