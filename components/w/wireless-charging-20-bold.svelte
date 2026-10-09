<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9abdnbmo.css';
import '../../css/q/q2o__te3v.css';
import '../../css/g/g4vsmpb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x9abdnbmo"/><path class="q2o__te3v"/><path class="g4vsmpb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wireless-charging-20-bold" {...props}></Icon>
