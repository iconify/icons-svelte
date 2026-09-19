<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zub42f2bw.css';
import '../../css/d/dcs2u9ork.css';
import '../../css/t/t-xa73ajk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="zub42f2bw"/><path class="dcs2u9ork"/><path clip-rule="evenodd" class="t-xa73ajk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:syringe-vaccine-outline" {...props}></Icon>
