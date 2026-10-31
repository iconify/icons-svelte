<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uxo1rzbps.css';
import '../../css/p/pt-1ib6kt.css';
import '../../css/o/o-cne-k-k.css';
import '../../css/j/jn737pbse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":150};
const content = `<g class="ft5dv1b6b"><path class="uxo1rzbps"/><path class="pt-1ib6kt"/><path class="o-cne-k-k"/><path class="jn737pbse"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cif:tl" {...props}></Icon>
