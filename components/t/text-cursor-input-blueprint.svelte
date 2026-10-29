<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/h/h5rhl3b_r.css';
import '../../css/x/xurpiib7h.css';
import '../../css/m/m-y2gobfk.css';
import '../../css/r/rqr48qurw.css';
import '../../css/n/nj1lohb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="h5rhl3b_r wm-deco"/><path class="wm-deco xurpiib7h"/><path class="m-y2gobfk wm-k"/><path class="rqr48qurw wm-k"/><path class="nj1lohb5m wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:text-cursor-input-blueprint" {...props}></Icon>
