<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqcchmb8c.css';
import '../../css/y/ymqda_bxj.css';
import '../../css/b/bufykz6nv.css';
import '../../css/z/zgtxh_b8y.css';
import '../../css/o/o-b6_hbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oqcchmb8c"/><path class="ymqda_bxj"/><path class="bufykz6nv"/><path class="zgtxh_b8y"/><path class="o-b6_hbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tree-planting-20-bold" {...props}></Icon>
