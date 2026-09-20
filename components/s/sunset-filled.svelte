<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elp_duv8g.css';
import '../../css/j/jl_m3bc1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="elp_duv8g"/><path class="jl_m3bc1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:sunset-filled" {...props}></Icon>
