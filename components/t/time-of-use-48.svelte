<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm295izdf.css';
import '../../css/f/faw5_bbxe.css';
import '../../css/l/lkg0w6bmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xm295izdf"/><path class="faw5_bbxe"/><path class="lkg0w6bmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:time-of-use-48" {...props}></Icon>
