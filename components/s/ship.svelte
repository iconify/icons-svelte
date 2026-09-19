<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cpspcpjsa.css';
import '../../css/c/csufotbpy.css';
import '../../css/j/ju-cazbvc.css';
import '../../css/q/qt2plpg1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="cpspcpjsa"/><path clip-rule="evenodd" class="csufotbpy"/><path clip-rule="evenodd" class="ju-cazbvc"/><path class="qt2plpg1d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:ship" {...props}></Icon>
