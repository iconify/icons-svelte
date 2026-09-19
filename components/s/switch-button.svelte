<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/f/fb3tv3bfw.css';
import '../../css/o/o3gfejbmt.css';
import '../../css/m/ma9v-ebqy.css';
import '../../css/t/tpuugf0vy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="fb3tv3bfw"/><path class="o3gfejbmt"/><path class="ma9v-ebqy"/><path class="tpuugf0vy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:switch-button" {...props}></Icon>
