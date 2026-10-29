<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/x/xlvdms2_b.css';
import '../../css/b/b8oq6jb1s.css';
import '../../css/e/egu5xwbsp.css';
import '../../css/k/k8u9w9nom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco xlvdms2_b"/><path class="b8oq6jb1s wm-deco"/><path class="egu5xwbsp wm-k"/><path class="k8u9w9nom wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:toggle-blueprint" {...props}></Icon>
