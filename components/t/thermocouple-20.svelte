<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwc8_0vln.css';
import '../../css/j/jwt9puapv.css';
import '../../css/h/hx1joebdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hwc8_0vln"/><path class="jwt9puapv"/><path class="hx1joebdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermocouple-20" {...props}></Icon>
