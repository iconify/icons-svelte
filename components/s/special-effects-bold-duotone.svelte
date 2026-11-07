<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg928d-qd.css';
import '../../css/l/lqupblb0q.css';
import '../../css/v/vx_l23zwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vg928d-qd"/><path class="lqupblb0q"/><path class="vx_l23zwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:special-effects-bold-duotone" {...props}></Icon>
