<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll0lbeozm.css';
import '../../css/j/jaxt8ed6x.css';
import '../../css/c/czwa2emeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ll0lbeozm"/><path class="jaxt8ed6x"/><path class="czwa2emeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:telemetry-20" {...props}></Icon>
