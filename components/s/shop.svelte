<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/f/fagbf2b8f.css';
import '../../css/x/x0yq8fapu.css';
import '../../css/r/r1o46bcgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="fagbf2b8f"/><path class="x0yq8fapu"/><path class="r1o46bcgn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:shop" {...props}></Icon>
