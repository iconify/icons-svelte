<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/m2t9gz_ls.css';
import '../../css/g/gg03weilf.css';
import '../../css/q/qt_qbll0w.css';
import '../../css/e/ei6c-pcgq.css';
import '../../css/d/d28jcob6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="m2t9gz_ls"/><path class="gg03weilf wm-k"/><path class="qt_qbll0w wm-a"/><path class="ei6c-pcgq wm-k"/><path class="d28jcob6c wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:trash-2-sketch" {...props}></Icon>
