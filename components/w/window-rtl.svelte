<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl1gw9yva.css';
import '../../css/g/gk_snkblx.css';
import '../../css/i/ifc5sxbuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sl1gw9yva"/><path class="gk_snkblx"/><circle class="ifc5sxbuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:window-rtl" {...props}></Icon>
