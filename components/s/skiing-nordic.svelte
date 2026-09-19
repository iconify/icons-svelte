<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti4q6eknm.css';
import '../../css/b/bsbfkackf.css';
import '../../css/k/k-gfreizg.css';
import '../../css/f/f0elirbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ti4q6eknm"><path class="bsbfkackf"/><path class="k-gfreizg"/><path class="f0elirbsr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:skiing-nordic" {...props}></Icon>
