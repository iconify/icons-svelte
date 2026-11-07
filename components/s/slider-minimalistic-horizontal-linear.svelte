<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/g0v39tb0j.css';
import '../../css/j/jmv52wbro.css';
import '../../css/r/r7ipq5s-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="g0v39tb0j"/><path class="jmv52wbro"/><path class="r7ipq5s-n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:slider-minimalistic-horizontal-linear" {...props}></Icon>
