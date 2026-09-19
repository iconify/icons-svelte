<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt_l_wkmq.css';
import '../../css/s/s_rh6-bjn.css';
import '../../css/r/rfmo84bve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dt_l_wkmq"/><path class="s_rh6-bjn"/><path class="rfmo84bve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:stockchart" {...props}></Icon>
