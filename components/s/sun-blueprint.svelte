<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/p/p6vy9kb5f.css';
import '../../css/f/feovcib_o.css';
import '../../css/z/z0temacgj.css';
import '../../css/k/kwzkbjbps.css';
import '../../css/z/zs295v-ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="p6vy9kb5f wm-deco"/><path class="feovcib_o wm-deco"/><path class="wm-deco z0temacgj"/><path class="kwzkbjbps wm-k"/><path class="wm-a zs295v-ni"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sun-blueprint" {...props}></Icon>
