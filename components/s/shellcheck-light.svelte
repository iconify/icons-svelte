<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq-d4ab0e.css';
import '../../css/v/vxe7b0b2d.css';
import '../../css/t/twij58b_v.css';
import '../../css/l/l79kylebl.css';
import '../../css/u/uy0hx2qfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="iq-d4ab0e"/><path class="vxe7b0b2d"/><path class="twij58b_v"/><path class="l79kylebl"/><path class="uy0hx2qfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:shellcheck-light" {...props}></Icon>
