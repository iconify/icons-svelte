<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lf8pxgdhs.css';
import '../../css/a/a5gobsblo.css';
import '../../css/e/ezzof15xj.css';
import '../../css/o/og0jb_tck.css';
import '../../css/c/cunejjbhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><circle class="lf8pxgdhs"/><path class="a5gobsblo"/><path class="ezzof15xj"/><path clip-rule="evenodd" class="og0jb_tck"/><path class="cunejjbhe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:signal-tower-bold" {...props}></Icon>
