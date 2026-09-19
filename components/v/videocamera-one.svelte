<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/e/eldoky0en.css';
import '../../css/a/ajxep-bpy.css';
import '../../css/q/qs645lbfc.css';
import '../../css/o/ohwln3bng.css';
import '../../css/j/jyjk2cs2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><rect class="eldoky0en"/><path class="ajxep-bpy"/><circle class="qs645lbfc"/><circle class="ohwln3bng"/><path class="jyjk2cs2r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:videocamera-one" {...props}></Icon>
