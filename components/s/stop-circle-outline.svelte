<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/u/u9mbdp5lw.css';
import '../../css/z/zt_l6p9nm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<g class="h01tyzbfu"><path class="u9mbdp5lw"/><path class="zt_l6p9nm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:stop-circle-outline" {...props}></Icon>
