<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/w/wo_zr_q_a.css';
import '../../css/s/szey3hb9c.css';
import '../../css/e/e7i2pvoaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="wo_zr_q_a"/><path class="szey3hb9c"/><circle class="e7i2pvoaw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:s-turn-down" {...props}></Icon>
