<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iquifubcu.css';
import '../../css/z/zm35_kbpi.css';
import '../../css/a/a75755bbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iquifubcu"/><path class="zm35_kbpi"/><path class="a75755bbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:shopping-shipping-delivery-person-motorcycle" {...props}></Icon>
