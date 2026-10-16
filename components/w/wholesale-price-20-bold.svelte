<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybbuh2wlg.css';
import '../../css/n/n7g_dgm_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ybbuh2wlg"/><path class="n7g_dgm_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wholesale-price-20-bold" {...props}></Icon>
