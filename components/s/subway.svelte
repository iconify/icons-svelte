<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b79z_ipds.css';
import '../../css/j/jma2uubte.css';
import '../../css/p/pcr75dyvp.css';
import '../../css/m/mu-e1vmsy.css';
import '../../css/e/ec7pvbb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><rect class="b79z_ipds"/><circle class="jma2uubte"/><circle class="pcr75dyvp"/><path class="mu-e1vmsy"/><path class="ec7pvbb9m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:subway" {...props}></Icon>
