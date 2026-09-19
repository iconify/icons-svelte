<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nctb2ac4r.css';
import '../../css/u/u7s_9vzkd.css';
import '../../css/o/o6l1_m8up.css';
import '../../css/o/o8_eirm0g.css';
import '../../css/w/w1b3o1jpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><g class="nctb2ac4r"><path clip-rule="evenodd" class="u7s_9vzkd"/><path class="o6l1_m8up"/></g><path clip-rule="evenodd" class="o8_eirm0g"/><path class="w1b3o1jpx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:speaker-low-print" {...props}></Icon>
