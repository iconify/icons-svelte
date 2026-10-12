<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xr984lbhp.css';
import '../../css/p/pk4v8xyym.css';
import '../../css/l/l4o7_jb9n.css';
import '../../css/z/zc-pre9pt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<g class="ft5dv1b6b"><rect class="xr984lbhp"/><rect class="pk4v8xyym"/><rect class="l4o7_jb9n"/><rect class="zc-pre9pt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:theauth" {...props}></Icon>
