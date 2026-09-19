<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/iopy05bgv.css';
import '../../css/z/zuilzvben.css';
import '../../css/r/rqvtl8brz.css';
import '../../css/s/sf-p1-qpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="iopy05bgv"/><path class="zuilzvben"/><path class="rqvtl8brz"/><path class="sf-p1-qpm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:two-factor-access" {...props}></Icon>
