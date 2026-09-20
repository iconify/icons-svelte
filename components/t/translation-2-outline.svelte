<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bom2j6ltg.css';
import '../../css/q/qzx8d-bpx.css';
import '../../css/y/ysalnkb3g.css';
import '../../css/q/qbm595m9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bom2j6ltg"/><path class="qzx8d-bpx"/><path clip-rule="evenodd" class="ysalnkb3g"/><path clip-rule="evenodd" class="qbm595m9m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:translation-2-outline" {...props}></Icon>
