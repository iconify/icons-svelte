<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/q/qp3509dce.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/f/fz9wbhbib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="qp3509dce wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="fz9wbhbib"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sidebar-blueprint" {...props}></Icon>
