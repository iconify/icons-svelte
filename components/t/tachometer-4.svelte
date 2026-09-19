<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g-briy-mv.css';
import '../../css/q/qhogk5bhw.css';
import '../../css/g/gyvacpo7m.css';
import '../../css/k/kr6zv5brr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="g-briy-mv"/><path class="qhogk5bhw"/><path class="gyvacpo7m"/><path class="kr6zv5brr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:tachometer-4" {...props}></Icon>
