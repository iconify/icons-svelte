<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/u/ubo2nlb6e.css';
import '../../css/m/mwa5mqb6p.css';
import '../../css/y/yr2f_fpsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ubo2nlb6e"/><circle class="mwa5mqb6p"/><path class="yr2f_fpsb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:user-unlock-01" {...props}></Icon>
