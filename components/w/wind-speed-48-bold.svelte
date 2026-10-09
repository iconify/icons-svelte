<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6u7_8bet.css';
import '../../css/c/con_q4m6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i6u7_8bet"/><path class="con_q4m6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-speed-48-bold" {...props}></Icon>
