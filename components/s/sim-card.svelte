<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r5rnlpo5e.css';
import '../../css/r/rmhzubc9s.css';
import '../../css/m/mn0jc5v_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="r5rnlpo5e"/><circle class="rmhzubc9s"/><path class="mn0jc5v_r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:sim-card" {...props}></Icon>
