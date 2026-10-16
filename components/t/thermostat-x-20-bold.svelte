<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvdded8zf.css';
import '../../css/n/nm0j_eisa.css';
import '../../css/h/hp8p1qxmm.css';
import '../../css/v/vkfkgacfm.css';
import '../../css/l/l3qindbue.css';
import '../../css/f/fdtytm4ox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fvdded8zf"/><path class="nm0j_eisa"/><path class="hp8p1qxmm"/><path class="vkfkgacfm"/><path class="l3qindbue"/><path class="fdtytm4ox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermostat-x-20-bold" {...props}></Icon>
