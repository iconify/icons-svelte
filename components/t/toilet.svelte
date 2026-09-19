<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/f/fqt00wfud.css';
import '../../css/z/zg5n0-bns.css';
import '../../css/p/pv42_gb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="fqt00wfud"/><path class="zg5n0-bns"/><path class="pv42_gb1e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:toilet" {...props}></Icon>
