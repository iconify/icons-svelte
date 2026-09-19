<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r3w5eyb_s.css';
import '../../css/f/f7vo7gb8u.css';
import '../../css/p/pd-w5_bbs.css';
import '../../css/o/oukt2hbfz.css';
import '../../css/e/eb3g_0bdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="r3w5eyb_s"/><path clip-rule="evenodd" class="f7vo7gb8u"/><path class="pd-w5_bbs"/><path clip-rule="evenodd" class="oukt2hbfz"/><path class="eb3g_0bdr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:seedling" {...props}></Icon>
