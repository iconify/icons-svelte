<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/ptk67nbuj.css';
import '../../css/q/qxpfaf6dk.css';
import '../../css/q/qle0cdbgv.css';
import '../../css/e/e0i688bvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ptk67nbuj"/><path clip-rule="evenodd" class="qxpfaf6dk"/><path class="qle0cdbgv"/><path clip-rule="evenodd" class="e0i688bvf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:search-tint-outline" {...props}></Icon>
