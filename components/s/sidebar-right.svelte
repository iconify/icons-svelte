<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqd8fcboz.css';
import '../../css/j/jw6_s00qn.css';
import '../../css/u/uhr2_rb0p.css';
import '../../css/c/caw_8nb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="hqd8fcboz"><path class="jw6_s00qn"/><path class="uhr2_rb0p"/><path class="caw_8nb8t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gala:sidebar-right" {...props}></Icon>
