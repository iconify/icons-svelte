<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mzv-97b_r.css';
import '../../css/b/bgu0hmbxv.css';
import '../../css/z/zn_5giv4w.css';
import '../../css/d/d2qkukb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="mzv-97b_r"/><path class="bgu0hmbxv"/><path class="zn_5giv4w"/><path class="d2qkukb0p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:two-triangles" {...props}></Icon>
