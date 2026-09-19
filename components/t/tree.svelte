<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xzfx_kbpp.css';
import '../../css/q/qn5kscbsg.css';
import '../../css/h/h_m7exbzz.css';
import '../../css/u/ugjqc-bch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="xzfx_kbpp"/><path class="qn5kscbsg"/><path clip-rule="evenodd" class="h_m7exbzz"/><path class="ugjqc-bch"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:tree" {...props}></Icon>
