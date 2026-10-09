<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4rl_dmmq.css';
import '../../css/z/z1x0aebyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r4rl_dmmq"/><path class="z1x0aebyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tidal-stream-turbine-20-bold" {...props}></Icon>
