<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wry8nmbpn.css';
import '../../css/c/crnolnb_i.css';
import '../../css/l/lak7f2bfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wry8nmbpn"/><path class="crnolnb_i"/><path class="lak7f2bfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wine-glass-48" {...props}></Icon>
