<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lpyr71bzg.css';
import '../../css/r/ryndaxq8c.css';
import '../../css/i/irudeebhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lpyr71bzg"/><path class="ryndaxq8c"/><path class="irudeebhr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:speaker-minimalistic-broken" {...props}></Icon>
