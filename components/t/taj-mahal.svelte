<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/x/xr_v0bl0a.css';
import '../../css/t/tm68yffwl.css';
import '../../css/i/in5lanbvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="xr_v0bl0a"/><path class="tm68yffwl"/><path class="in5lanbvd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:taj-mahal" {...props}></Icon>
