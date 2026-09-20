<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/l_vfulbig.css';
import '../../css/f/fyzqmibvv.css';
import '../../css/z/z1yj6sbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l_vfulbig"/><path class="fyzqmibvv"/><path class="z1yj6sbtc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:waterdrops-linear" {...props}></Icon>
