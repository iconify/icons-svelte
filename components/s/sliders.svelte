<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/l/lz9qfxb6b.css';
import '../../css/v/v9almc-9r.css';
import '../../css/u/u0l9fhfjn.css';
import '../../css/l/lfijr0r5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="lz9qfxb6b"/><path class="v9almc-9r"/><path class="u0l9fhfjn"/><path class="lfijr0r5r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:sliders" {...props}></Icon>
