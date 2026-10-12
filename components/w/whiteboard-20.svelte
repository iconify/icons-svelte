<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mriwaebth.css';
import '../../css/q/q2a0nbcka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mriwaebth"/><path class="q2a0nbcka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:whiteboard-20" {...props}></Icon>
