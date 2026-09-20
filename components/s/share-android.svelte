<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cy4sqnj9t.css';
import '../../css/w/wms1q8geo.css';
import '../../css/o/ofhvs956t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="cy4sqnj9t"/><path clip-rule="evenodd" class="wms1q8geo"/><path class="ofhvs956t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:share-android" {...props}></Icon>
