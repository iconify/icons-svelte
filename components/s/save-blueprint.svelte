<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/d/d38lhlb2a.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/a/aw_udabwt.css';
import '../../css/t/t2srnhboy.css';
import '../../css/k/kiim2mb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="d38lhlb2a wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="aw_udabwt wm-k"/><path class="t2srnhboy wm-a"/><path class="kiim2mb2c wm-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:save-blueprint" {...props}></Icon>
