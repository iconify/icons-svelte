<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7ooaebqk.css';
import '../../css/t/tqod06aih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v7ooaebqk"/><path class="tqod06aih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:shopping-shipping-delivery-truck" {...props}></Icon>
