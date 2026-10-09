<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlbvg8bgk.css';
import '../../css/a/ax-mmibru.css';
import '../../css/v/vyx3_bcxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mlbvg8bgk"/><path class="ax-mmibru"/><path class="vyx3_bcxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sleet-20-bold" {...props}></Icon>
