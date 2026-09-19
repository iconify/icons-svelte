<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/x/xhdah4bbl.css';
import '../../css/f/fsan3yarc.css';
import '../../css/l/l5tjo4bak.css';
import '../../css/x/xbrl61bjm.css';
import '../../css/e/ed8432ijo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="xhdah4bbl"/><rect class="fsan3yarc"/><rect class="l5tjo4bak"/><rect class="xbrl61bjm"/><rect class="ed8432ijo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:view-grid-card" {...props}></Icon>
