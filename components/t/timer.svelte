<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/b/bwjoyu67r.css';
import '../../css/f/fhcsjwttb.css';
import '../../css/x/x-adczucl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="bwjoyu67r"/><circle class="fhcsjwttb"/><path class="x-adczucl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:timer" {...props}></Icon>
