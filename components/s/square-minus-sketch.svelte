<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/j6iui7arm.css';
import '../../css/g/gduuvtb0e.css';
import '../../css/a/awk9_jbks.css';
import '../../css/j/jk40j7w3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="j6iui7arm"/><path class="gduuvtb0e wm-k"/><path class="awk9_jbks wm-a"/><path class="jk40j7w3r wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:square-minus-sketch" {...props}></Icon>
