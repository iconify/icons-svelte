<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/l/lxx50rbdy.css';
import '../../css/v/vugmo3b-s.css';
import '../../css/k/ko5q309hq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="lxx50rbdy"/><path class="vugmo3b-s"/><path class="ko5q309hq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:vicia-faba" {...props}></Icon>
