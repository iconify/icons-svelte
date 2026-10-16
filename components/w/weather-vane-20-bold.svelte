<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz6k66c-q.css';
import '../../css/r/rkadl_r6j.css';
import '../../css/t/tcaouzbll.css';
import '../../css/m/meg5fm1wc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xz6k66c-q"/><path class="rkadl_r6j"/><path class="tcaouzbll"/><path class="meg5fm1wc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:weather-vane-20-bold" {...props}></Icon>
