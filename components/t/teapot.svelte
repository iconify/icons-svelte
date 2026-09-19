<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/k/kv2m18g6m.css';
import '../../css/d/do_ciqhik.css';
import '../../css/v/voz9ctthh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="kv2m18g6m"/><path class="do_ciqhik"/><path class="voz9ctthh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:teapot" {...props}></Icon>
