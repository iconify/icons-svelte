<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/rma5_ql1e.css';
import '../../css/m/migl5jbsu.css';
import '../../css/b/beaeuqbls.css';
import '../../css/a/a8a2mlbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rma5_ql1e"/><path class="migl5jbsu"/><path class="beaeuqbls"/><path class="a8a2mlbtc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:siderbar-linear" {...props}></Icon>
