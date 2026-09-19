<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/p/psukg5b1p.css';
import '../../css/j/jz7w11b0h.css';
import '../../css/u/uu0aqvb3g.css';
import '../../css/d/d1x0gkpom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="psukg5b1p"/><circle class="jz7w11b0h"/><path class="uu0aqvb3g"/><path class="d1x0gkpom"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:sickbed" {...props}></Icon>
