<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/a/acgf497pn.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/s/so7639bqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="acgf497pn wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="so7639bqv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:square-blueprint" {...props}></Icon>
