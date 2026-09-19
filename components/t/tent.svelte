<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kc_uuzb-u.css';
import '../../css/d/dpgvrjd0j.css';
import '../../css/v/vyk1e9bbt.css';
import '../../css/t/trbaiac_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="kc_uuzb-u"/><path class="dpgvrjd0j"/><path class="vyk1e9bbt"/><path class="trbaiac_h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:tent" {...props}></Icon>
