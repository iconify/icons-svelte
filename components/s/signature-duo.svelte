<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n4qn6957a.css';
import '../../css/i/ir3ncbbaj.css';
import '../../css/t/ttmv56b5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="n4qn6957a"/><path clip-rule="evenodd" class="ir3ncbbaj"/><path class="ttmv56b5u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:signature-duo" {...props}></Icon>
