<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqwmttb_b.css';
import '../../css/r/r_ehnoaxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wqwmttb_b"/><path class="r_ehnoaxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:trending-down-48" {...props}></Icon>
