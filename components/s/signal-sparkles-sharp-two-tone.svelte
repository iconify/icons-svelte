<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/r/rq4oyob_i.css';
import '../../css/t/tip7h1kfk.css';
import '../../css/y/yd_c7gd8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="rq4oyob_i"/><path class="tip7h1kfk"/><path class="yd_c7gd8z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:signal-sparkles-sharp-two-tone" {...props}></Icon>
