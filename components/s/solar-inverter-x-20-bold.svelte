<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9k69ztaq.css';
import '../../css/c/clp87tp4c.css';
import '../../css/l/l3qindbue.css';
import '../../css/f/fdtytm4ox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q9k69ztaq"/><path class="clp87tp4c"/><path class="l3qindbue"/><path class="fdtytm4ox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-inverter-x-20-bold" {...props}></Icon>
