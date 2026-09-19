<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/s/shidfnbcb.css';
import '../../css/x/xgjnkbdze.css';
import '../../css/i/i-3wzrbog.css';
import '../../css/l/l1lz8dbkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="shidfnbcb"/><path class="xgjnkbdze"/><path class="i-3wzrbog"/><path class="l1lz8dbkq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:set-off" {...props}></Icon>
