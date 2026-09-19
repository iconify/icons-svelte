<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq1lkzb4i.css';
import '../../css/y/ykrh_um7r.css';
import '../../css/l/ltn1tccxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="pq1lkzb4i"><path class="ykrh_um7r"/><path class="ltn1tccxu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:xigua" {...props}></Icon>
