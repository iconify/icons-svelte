<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/l/lynb7gb5s.css';
import '../../css/e/ei9w4bc3h.css';
import '../../css/t/tbgu7rb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g class="bi12bsetm"><path class="lynb7gb5s"/><path class="ei9w4bc3h"/><path class="tbgu7rb4e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:tv-mode" {...props}></Icon>
