<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4e3b0h7s.css';
import '../../css/x/x0u-ch0td.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c4e3b0h7s"/><path class="x0u-ch0td"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:shopping-shipping-bag-2" {...props}></Icon>
