<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/m/m1z-ndv6m.css';
import '../../css/m/mxuiqbdgj.css';
import '../../css/l/lj14h_baz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="m1z-ndv6m"/><path class="mxuiqbdgj"/><path class="lj14h_baz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:signal-medium-sharp-duotone" {...props}></Icon>
