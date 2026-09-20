<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mcixzjbbg.css';
import '../../css/q/qm1os7wyx.css';
import '../../css/l/llumy86rg.css';
import '../../css/b/br4x3j_5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":280,"height":110};
const content = `<g class="ft5dv1b6b"><path class="mcixzjbbg"/><path class="qm1os7wyx"/><path class="llumy86rg"/><path class="br4x3j_5c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:standard-chartered" {...props}></Icon>
