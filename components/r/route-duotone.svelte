<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r4wggfb6m.css';
import '../../css/x/xtn-lpbad.css';
import '../../css/k/kkc51l8ou.css';
import '../../css/y/y3pbk0kao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r4wggfb6m"/><path class="xtn-lpbad"/><path class="kkc51l8ou"/><path class="y3pbk0kao"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:route-duotone" {...props}></Icon>
