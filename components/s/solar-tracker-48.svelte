<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlo-1-b1r.css';
import '../../css/u/u95w5ybee.css';
import '../../css/z/z7ly-0cgq.css';
import '../../css/h/ha43yw8ah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tlo-1-b1r"/><path class="u95w5ybee"/><path class="z7ly-0cgq"/><path class="ha43yw8ah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-tracker-48" {...props}></Icon>
