<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xvhdk6bks.css';
import '../../css/r/rzzzk2g-f.css';
import '../../css/t/tn0uqua-i.css';
import '../../css/f/fsyzf-b_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="xvhdk6bks"/><path class="rzzzk2g-f"/><circle class="tn0uqua-i"/><path class="fsyzf-b_i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:ssd" {...props}></Icon>
