<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wnv2-o6qc.css';
import '../../css/v/vcx3bpbyi.css';
import '../../css/m/mld737bxo.css';
import '../../css/g/g4b4u9bph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="wnv2-o6qc"/><path class="vcx3bpbyi"/><path clip-rule="evenodd" class="mld737bxo"/><path class="g4b4u9bph"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:tree-1" {...props}></Icon>
