<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/j1c5z9bpg.css';
import '../../css/b/b5krwpbty.css';
import '../../css/t/t4ya6qb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="j1c5z9bpg"/><path class="b5krwpbty wm-shadow"/><path class="t4ya6qb4m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:signal-engrave" {...props}></Icon>
