<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g6vt25bsd.css';
import '../../css/r/rfkvs9bdx.css';
import '../../css/l/l_2ml6bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="g6vt25bsd"/><circle class="rfkvs9bdx"/><rect class="l_2ml6bep"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:sim-card" {...props}></Icon>
