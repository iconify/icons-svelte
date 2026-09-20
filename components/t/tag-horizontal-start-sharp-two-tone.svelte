<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/a/alk7dvb9p.css';
import '../../css/g/gfnhmpggj.css';
import '../../css/m/mabku0myx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="alk7dvb9p"/><path class="gfnhmpggj"/><path class="mabku0myx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:tag-horizontal-start-sharp-two-tone" {...props}></Icon>
