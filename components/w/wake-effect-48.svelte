<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_4l3dbra.css';
import '../../css/r/r5t_d6bdj.css';
import '../../css/m/m9x6imbjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z_4l3dbra"/><path class="r5t_d6bdj"/><path class="m9x6imbjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wake-effect-48" {...props}></Icon>
