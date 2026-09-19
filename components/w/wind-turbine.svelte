<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/onf15_b7f.css';
import '../../css/s/s0r1bobkf.css';
import '../../css/p/povs420wf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="onf15_b7f"/><path class="s0r1bobkf"/><circle class="povs420wf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:wind-turbine" {...props}></Icon>
