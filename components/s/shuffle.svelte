<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0_da6b0m.css';
import '../../css/z/zr3e3667p.css';
import '../../css/u/uw0f56fmz.css';
import '../../css/k/k0lfk7b3s.css';
import '../../css/l/l-ttvnh_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0_da6b0m wm-shadow"/><path class="wm-k zr3e3667p"/><path class="uw0f56fmz wm-k"/><path class="k0lfk7b3s wm-a"/><path class="l-ttvnh_e wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:shuffle" {...props}></Icon>
