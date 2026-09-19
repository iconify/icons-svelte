<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/o/ozgrq5b1r.css';
import '../../css/l/l7avsacre.css';
import '../../css/q/qfez7pbdx.css';
import '../../css/b/bbx74dvkh.css';
import '../../css/f/f08pkdblx.css';
import '../../css/v/vdhgeqfxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="ozgrq5b1r"/><circle class="l7avsacre"/><circle class="qfez7pbdx"/><circle class="bbx74dvkh"/><path class="f08pkdblx"/><path class="vdhgeqfxw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:whole-site-accelerator" {...props}></Icon>
