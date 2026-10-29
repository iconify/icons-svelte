<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/i_1xs8ezl.css';
import '../../css/j/jcugpbcrt.css';
import '../../css/e/erfo6-egg.css';
import '../../css/p/psaadlbfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="i_1xs8ezl"/><path class="jcugpbcrt wm-k"/><path class="erfo6-egg wm-k"/><path class="psaadlbfa wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:signpost-sketch" {...props}></Icon>
