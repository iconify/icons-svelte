<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/x/xib2qv12u.css';
import '../../css/r/r_69r9b3c.css';
import '../../css/h/hbfbrwbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="xib2qv12u"/><path class="r_69r9b3c"/><path class="hbfbrwbos"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:surveillance-cameras" {...props}></Icon>
