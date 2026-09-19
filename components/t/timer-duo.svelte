<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/it_b6ibho.css';
import '../../css/c/cwnti_bpv.css';
import '../../css/c/cup7wj97d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="it_b6ibho"/><path class="cwnti_bpv"/><path class="cup7wj97d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:timer-duo" {...props}></Icon>
