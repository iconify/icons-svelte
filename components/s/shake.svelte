<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/n/n4ox84buf.css';
import '../../css/y/yzv3l5g3i.css';
import '../../css/a/a5qmfbb0q.css';
import '../../css/x/x24d_rjaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="n4ox84buf"/><path class="yzv3l5g3i"/><path class="a5qmfbb0q"/><path class="x24d_rjaf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:shake" {...props}></Icon>
