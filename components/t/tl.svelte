<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bmggirfyq.css';
import '../../css/d/d-5fc0ryw.css';
import '../../css/o/o-cne-k-k.css';
import '../../css/e/ehn2nbutb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":150};
const content = `<g class="ft5dv1b6b"><path class="bmggirfyq"/><path class="d-5fc0ryw"/><path class="o-cne-k-k"/><path class="ehn2nbutb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cif:tl" {...props}></Icon>
