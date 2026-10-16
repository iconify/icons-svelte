<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsiiptbtu.css';
import '../../css/d/dm-cxkseg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qsiiptbtu"/><path class="dm-cxkseg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shopping-basket-48-bold" {...props}></Icon>
