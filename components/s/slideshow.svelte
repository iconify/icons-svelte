<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/k/kag80rb4s.css';
import '../../css/h/hex-lic2x.css';
import '../../css/d/dmc_suboo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kag80rb4s"/><path class="hex-lic2x"/><path class="dmc_suboo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:slideshow" {...props}></Icon>
