<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/z/z-8jtj9vd.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/l/lqm3yub_u.css';
import '../../css/j/jfru2eb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco z-8jtj9vd"/><path class="cf3uzcrzx wm-deco"/><path class="lqm3yub_u wm-k"/><path class="jfru2eb2v wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:weight-blueprint" {...props}></Icon>
