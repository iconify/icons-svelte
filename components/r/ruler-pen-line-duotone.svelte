<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hgrm2rbfz.css';
import '../../css/t/tnnk9dqhq.css';
import '../../css/s/sjq--8btf.css';
import '../../css/h/h-mw_xb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hgrm2rbfz"/><path class="tnnk9dqhq"/><path class="sjq--8btf"/><path class="h-mw_xb8f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ruler-pen-line-duotone" {...props}></Icon>
