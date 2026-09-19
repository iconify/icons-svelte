<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/r/rea5bibqm.css';
import '../../css/l/lh3k6dbwo.css';
import '../../css/h/hwf0aab2i.css';
import '../../css/j/jcocdpb8j.css';
import '../../css/s/sr6x3ialb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="rea5bibqm"/><path class="lh3k6dbwo"/><path class="hwf0aab2i"/><path class="jcocdpb8j"/><path class="sr6x3ialb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:sim" {...props}></Icon>
