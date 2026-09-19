<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/q/qmmnpqd0d.css';
import '../../css/k/kej97abdp.css';
import '../../css/c/cmqybvbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="qmmnpqd0d"/><path class="kej97abdp"/><path class="cmqybvbeu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:sunshade" {...props}></Icon>
