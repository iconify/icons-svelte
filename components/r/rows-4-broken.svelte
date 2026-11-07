<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/l4trkhdsa.css';
import '../../css/w/ws8s-nbqi.css';
import '../../css/w/wip28lbxr.css';
import '../../css/j/jtpwddb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l4trkhdsa"/><path class="ws8s-nbqi"/><path class="wip28lbxr"/><path class="jtpwddb9o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rows-4-broken" {...props}></Icon>
