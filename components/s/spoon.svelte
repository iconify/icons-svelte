<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/f/fo9q7n9ez.css';
import '../../css/o/ocruyxbsi.css';
import '../../css/q/qoybt6q_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><rect class="fo9q7n9ez"/><path class="ocruyxbsi"/><rect class="qoybt6q_l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:spoon" {...props}></Icon>
