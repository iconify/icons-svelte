<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jxz04mbly.css';
import '../../css/m/m_rt4_bcb.css';
import '../../css/v/vuso242af.css';
import '../../css/q/qxsgg6psh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="jxz04mbly"/><path class="m_rt4_bcb"/><path class="vuso242af"/><path class="qxsgg6psh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:van-bold" {...props}></Icon>
