<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/j/j9vg3_jgc.css';
import '../../css/s/skrettb2q.css';
import '../../css/h/hmcoah3hh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="j9vg3_jgc"/><path class="skrettb2q"/><path class="hmcoah3hh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:unlock" {...props}></Icon>
