<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bdqapd8qi.css';
import '../../css/k/k6zc6ccgf.css';
import '../../css/w/w92r_czij.css';
import '../../css/q/q3fe9qb1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bdqapd8qi wm-k"/><path class="k6zc6ccgf wm-a"/><path class="w92r_czij wm-k"/><path class="q3fe9qb1y wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:waves-sketch" {...props}></Icon>
