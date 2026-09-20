<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pxm7_12cz.css';
import '../../css/u/u8gkuv4uz.css';
import '../../css/c/cfw654b4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pxm7_12cz"/><path class="u8gkuv4uz"/><path class="cfw654b4b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:stopwatch-broken" {...props}></Icon>
