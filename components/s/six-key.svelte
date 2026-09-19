<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/n/n03w5kbkh.css';
import '../../css/b/bdnk3hued.css';
import '../../css/g/gzi1ffbys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><rect class="n03w5kbkh"/><path class="bdnk3hued"/><path class="gzi1ffbys"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:six-key" {...props}></Icon>
