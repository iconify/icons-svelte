<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/j/jp9fg595t.css';
import '../../css/a/a3k-1f3du.css';
import '../../css/e/e625k9alo.css';
import '../../css/y/yo_phy9yo.css';
import '../../css/e/e0poc-59r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="jp9fg595t wm-deco"/><path class="a3k-1f3du wm-deco"/><circle class="e625k9alo wm-k"/><path class="wm-k yo_phy9yo"/><path class="e0poc-59r wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:wifi-off-blueprint" {...props}></Icon>
