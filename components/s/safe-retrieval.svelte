<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/a/adxs15bqu.css';
import '../../css/v/vay9-8v2p.css';
import '../../css/n/n3f4a3bix.css';
import '../../css/t/t0uw7wbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="adxs15bqu"/><path class="vay9-8v2p"/><path class="n3f4a3bix"/><path class="t0uw7wbmr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:safe-retrieval" {...props}></Icon>
