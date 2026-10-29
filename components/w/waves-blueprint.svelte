<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/l/ldjp7fxzo.css';
import '../../css/v/vkhck6o7w.css';
import '../../css/g/grta0fb4t.css';
import '../../css/d/d4oewab_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="ldjp7fxzo wm-deco"/><path class="vkhck6o7w wm-deco"/><path class="grta0fb4t wm-k"/><path class="d4oewab_d wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:waves-blueprint" {...props}></Icon>
