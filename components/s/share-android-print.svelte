<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rqp_fpfgv.css';
import '../../css/h/hku-2nb6r.css';
import '../../css/n/ne9k0gz5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="rqp_fpfgv"/><path clip-rule="evenodd" class="hku-2nb6r"/><path class="ne9k0gz5r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:share-android-print" {...props}></Icon>
