<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/k/kml1eewvt.css';
import '../../css/g/gbvfgr_zm.css';
import '../../css/p/pjwppjbhu.css';
import '../../css/s/sjq61vbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="kml1eewvt"/><path class="gbvfgr_zm"/><path class="pjwppjbhu"/><path class="sjq61vbaj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:ruler-trinangle-outline" {...props}></Icon>
