<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4x3c_beq.css';
import '../../css/k/k8ixw89dy.css';
import '../../css/c/cbp_2nbuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n4x3c_beq"/><path class="k8ixw89dy"/><circle class="cbp_2nbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:user-pages-rtl" {...props}></Icon>
