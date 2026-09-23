<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/m/ml6y6ub5c.css';
import '../../css/q/q-x02trva.css';
import '../../css/h/hlvcfl71u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ml6y6ub5c"/><path class="q-x02trva"/><path class="hlvcfl71u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:tag-sparkles-sharp-two-tone" {...props}></Icon>
