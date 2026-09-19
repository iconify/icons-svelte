<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/a/a008irbqj.css';
import '../../css/w/wjmydx_nr.css';
import '../../css/g/g-j2jqb9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="a008irbqj"/><path class="wjmydx_nr"/><path class="g-j2jqb9k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:vegetables" {...props}></Icon>
