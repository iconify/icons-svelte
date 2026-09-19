<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/f/fm3ditb9p.css';
import '../../css/q/q2-84bbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="fm3ditb9p"/><circle class="q2-84bbxm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:stapler" {...props}></Icon>
