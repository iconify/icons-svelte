<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lbbc56xbn.css';
import '../../css/l/l35_cxukk.css';
import '../../css/p/pdx-mjvpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="lbbc56xbn"/><path clip-rule="evenodd" class="l35_cxukk"/><path class="pdx-mjvpo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:t-shirt-print" {...props}></Icon>
