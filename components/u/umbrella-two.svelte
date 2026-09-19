<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/z/zio0--bwu.css';
import '../../css/h/hdbq3cbgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="zio0--bwu"/><path class="hdbq3cbgp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:umbrella-two" {...props}></Icon>
