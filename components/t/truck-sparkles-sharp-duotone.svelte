<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/c/cdixm-bmx.css';
import '../../css/z/zr5m9kbwl.css';
import '../../css/z/zzqgx-_3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="cdixm-bmx"/><path class="zr5m9kbwl"/><path class="zzqgx-_3m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:truck-sparkles-sharp-duotone" {...props}></Icon>
