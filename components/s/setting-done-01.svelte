<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hwhqdac_e.css';
import '../../css/c/cc0yg-bhd.css';
import '../../css/j/jy51gjgdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hwhqdac_e"/><path class="cc0yg-bhd"/><path class="jy51gjgdv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:setting-done-01" {...props}></Icon>
