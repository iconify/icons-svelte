<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/flz1i8pyj.css';
import '../../css/e/evvf81f4r.css';
import '../../css/m/mwwapo85f.css';
import '../../css/r/rd_no8yio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="flz1i8pyj"/><path class="evvf81f4r"/><path class="mwwapo85f"/><circle class="rd_no8yio"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:shrimp" {...props}></Icon>
