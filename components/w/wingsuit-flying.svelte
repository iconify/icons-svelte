<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti4q6eknm.css';
import '../../css/b/bsbfkackf.css';
import '../../css/b/bf_msp58c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ti4q6eknm"><path class="bsbfkackf"/><path class="bf_msp58c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:wingsuit-flying" {...props}></Icon>
