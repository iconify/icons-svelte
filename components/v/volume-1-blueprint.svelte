<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/l/lxrhnunmy.css';
import '../../css/y/y8trhedqw.css';
import '../../css/f/fz_4tjbyu.css';
import '../../css/y/ydfqvnb5a.css';
import '../../css/t/t3k6m9l_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="lxrhnunmy wm-deco"/><path class="wm-deco y8trhedqw"/><path class="fz_4tjbyu wm-k"/><path class="wm-a ydfqvnb5a"/><path class="t3k6m9l_o wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:volume-1-blueprint" {...props}></Icon>
