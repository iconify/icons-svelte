<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/w/w33rvnbme.css';
import '../../css/w/w575o1bvn.css';
import '../../css/c/currik_tu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="w33rvnbme"/><path class="w575o1bvn"/><path class="currik_tu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sticky-note-sparkles-sharp-duotone" {...props}></Icon>
