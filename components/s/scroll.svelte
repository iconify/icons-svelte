<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jfamqvjas.css';
import '../../css/h/hjrj_fbxo.css';
import '../../css/l/luctw4btv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="jfamqvjas"/><path class="hjrj_fbxo"/><path clip-rule="evenodd" class="luctw4btv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:scroll" {...props}></Icon>
