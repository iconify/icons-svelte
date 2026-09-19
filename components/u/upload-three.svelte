<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/u/utf5_xbzs.css';
import '../../css/i/i-0o_641g.css';
import '../../css/h/hjnl4zguy.css';
import '../../css/z/zyl4k9yjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="utf5_xbzs"/><path class="i-0o_641g"/><path class="hjnl4zguy"/><path class="zyl4k9yjq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:upload-three" {...props}></Icon>
