<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/o/o8be8xbcw.css';
import '../../css/x/x9ot73b2p.css';
import '../../css/h/hghintd6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="o8be8xbcw"/><path class="x9ot73b2p"/><path class="hghintd6i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:zoom-out" {...props}></Icon>
