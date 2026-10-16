<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvdded8zf.css';
import '../../css/n/nm0j_eisa.css';
import '../../css/h/hp8p1qxmm.css';
import '../../css/v/vkfkgacfm.css';
import '../../css/a/asc4-fm2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fvdded8zf"/><path class="nm0j_eisa"/><path class="hp8p1qxmm"/><path class="vkfkgacfm"/><path class="asc4-fm2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermostat-check-20-bold" {...props}></Icon>
