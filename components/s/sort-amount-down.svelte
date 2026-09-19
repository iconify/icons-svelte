<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pyewybbeq.css';
import '../../css/b/btrew6bni.css';
import '../../css/n/nmxnfxicr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="pyewybbeq"/><path class="btrew6bni"/><path class="nmxnfxicr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:sort-amount-down" {...props}></Icon>
