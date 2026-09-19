<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmtbg17_s.css';
import '../../css/v/vcrk3tb3p.css';
import '../../css/k/k7unic_8x.css';
import '../../css/b/b_4g56b9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cmtbg17_s"/><path class="vcrk3tb3p"/><path class="k7unic_8x"/><circle class="b_4g56b9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:walk" {...props}></Icon>
