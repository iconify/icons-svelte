<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxfeshb7a.css';
import '../../css/u/u8bokm_su.css';
import '../../css/m/mpk28w9ff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dxfeshb7a"/><path class="u8bokm_su"/><path class="mpk28w9ff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-inverter-check-20" {...props}></Icon>
