<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mwbwo4bgu.css';
import '../../css/l/lft_p3rrx.css';
import '../../css/d/dn2n-ml1t.css';
import '../../css/m/mo5netbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="mwbwo4bgu"/><path clip-rule="evenodd" class="lft_p3rrx"/><path clip-rule="evenodd" class="dn2n-ml1t"/><path class="mo5netbri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:smartphone-cutout-off" {...props}></Icon>
