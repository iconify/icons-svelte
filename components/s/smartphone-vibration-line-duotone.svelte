<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/m9lr-xbek.css';
import '../../css/i/iwzbdbrcw.css';
import '../../css/u/uh1sxf1kh.css';
import '../../css/j/jm518nbhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="m9lr-xbek"/><path class="iwzbdbrcw"/><path class="uh1sxf1kh"/><path class="jm518nbhy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smartphone-vibration-line-duotone" {...props}></Icon>
