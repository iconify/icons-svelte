<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/n/nhhjpt21o.css';
import '../../css/k/kosv92b2z.css';
import '../../css/m/mv_citbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="nhhjpt21o"/><path class="kosv92b2z"/><circle class="mv_citbmv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:u-turn-left" {...props}></Icon>
