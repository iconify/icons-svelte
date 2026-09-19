<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbk05b36b.css';
import '../../css/n/nv9qcacyl.css';
import '../../css/f/fgo_pksht.css';
import '../../css/p/ph3jxnbzf.css';
import '../../css/o/oafavueaw.css';
import '../../css/g/ggalogbdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<defs><clipPath id="SVGSJkC5dXi"><path class="nbk05b36b"/></clipPath></defs><g clip-path="url(#SVGSJkC5dXi)" transform="scale(.9375)" class="nv9qcacyl"><path class="fgo_pksht"/><path class="ph3jxnbzf"/><path class="oafavueaw"/><path class="ggalogbdw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:sd-4x3" {...props}></Icon>
