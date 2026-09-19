<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btx30rb9t.css';
import '../../css/i/i_r28w9ux.css';
import '../../css/j/jtnxt2mdt.css';
import '../../css/d/dp_ikp1ml.css';
import '../../css/t/tvs3vrs6f.css';
import '../../css/q/q4q6pohrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="btx30rb9t"><path class="i_r28w9ux"/><path class="jtnxt2mdt"/><path class="dp_ikp1ml"/><path class="tvs3vrs6f"/><path class="q4q6pohrs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:skiing-nordic" {...props}></Icon>
