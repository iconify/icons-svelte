<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrui74b0l.css';
import '../../css/r/r-3q_9bym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vrui74b0l"/><path class="r-3q_9bym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:toggle-off" {...props}></Icon>
