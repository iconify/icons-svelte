<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2nvqgbuj.css';
import '../../css/x/xadjgxb-b.css';
import '../../css/c/cni6_d2wb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i2nvqgbuj"/><path class="xadjgxb-b"/><path class="cni6_d2wb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:wifi-sharp" {...props}></Icon>
