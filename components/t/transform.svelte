<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/u/umfll9bys.css';
import '../../css/c/ceqznzypa.css';
import '../../css/h/h77qjobjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="umfll9bys"/><circle class="ceqznzypa"/><path class="h77qjobjk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:transform" {...props}></Icon>
