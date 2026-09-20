<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/j/jus-9cble.css';
import '../../css/r/r0fzdm12c.css';
import '../../css/l/l18eabbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jus-9cble"/><path class="r0fzdm12c"/><path class="l18eabbfs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:volume-off-sharp-two-tone" {...props}></Icon>
