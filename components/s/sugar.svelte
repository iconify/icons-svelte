<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/j/jvn-yrvsr.css';
import '../../css/p/pfcofkbgs.css';
import '../../css/n/ng_xb_b3f.css';
import '../../css/p/pice2pb4o.css';
import '../../css/o/o2x36accw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="jvn-yrvsr"/><path class="pfcofkbgs"/><path class="ng_xb_b3f"/><path class="pice2pb4o"/><path class="o2x36accw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:sugar" {...props}></Icon>
