<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/w/w30tc0baw.css';
import '../../css/w/ws3ndf7es.css';
import '../../css/h/h5rxt79wz.css';
import '../../css/d/d8hvsle5g.css';
import '../../css/x/xpahp5btp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="w30tc0baw wm-deco"/><path class="wm-deco ws3ndf7es"/><path class="h5rxt79wz wm-deco"/><path class="d8hvsle5g"/><path class="xpahp5btp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:thandai-blueprint" {...props}></Icon>
