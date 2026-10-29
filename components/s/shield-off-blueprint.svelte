<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/i/ibpnj1b4u.css';
import '../../css/r/rbzq4bjzv.css';
import '../../css/g/gcz3jrbxo.css';
import '../../css/g/gwhk54bhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="ibpnj1b4u wm-deco"/><path class="rbzq4bjzv wm-deco"/><path class="gcz3jrbxo wm-k"/><path class="gwhk54bhf wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shield-off-blueprint" {...props}></Icon>
