<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xwey4ebcb.css';
import '../../css/k/kw_djybrm.css';
import '../../css/u/u4tr0j94d.css';
import '../../css/e/ea361u4-y.css';
import '../../css/p/piztulodx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xwey4ebcb"/><path clip-rule="evenodd" class="kw_djybrm"/><path class="u4tr0j94d"/><path clip-rule="evenodd" class="ea361u4-y"/><path class="piztulodx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:sa" {...props}></Icon>
