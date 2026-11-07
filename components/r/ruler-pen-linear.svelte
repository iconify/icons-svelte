<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/oo2qfubvl.css';
import '../../css/q/qu7r9f2pl.css';
import '../../css/c/c9dh15yvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="oo2qfubvl"/><path class="qu7r9f2pl"/><path class="c9dh15yvi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ruler-pen-linear" {...props}></Icon>
