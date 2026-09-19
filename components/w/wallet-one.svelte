<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mvkzdkbth.css';
import '../../css/j/jiqqgjbyl.css';
import '../../css/q/qdwhrdl3w.css';
import '../../css/z/zwmgmbqzr.css';
import '../../css/r/r7k436bkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><rect class="mvkzdkbth"/><rect class="jiqqgjbyl"/><path class="qdwhrdl3w"/><path class="zwmgmbqzr"/><circle class="r7k436bkt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:wallet-one" {...props}></Icon>
