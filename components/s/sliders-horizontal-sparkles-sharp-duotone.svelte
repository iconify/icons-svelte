<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/c/cdvt0cjgt.css';
import '../../css/r/r-7n0qcfw.css';
import '../../css/s/snibgdcaa.css';
import '../../css/s/skqfcdqhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="cdvt0cjgt"/><path class="r-7n0qcfw"/><path class="snibgdcaa"/><path class="skqfcdqhg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sliders-horizontal-sparkles-sharp-duotone" {...props}></Icon>
