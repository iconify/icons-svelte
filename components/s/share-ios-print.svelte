<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gircq4sqa.css';
import '../../css/a/a9wz156rm.css';
import '../../css/g/gye5x8kso.css';
import '../../css/f/fhcdiobpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="gircq4sqa"/><path class="a9wz156rm"/><path class="gye5x8kso"/><path class="fhcdiobpo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:share-ios-print" {...props}></Icon>
