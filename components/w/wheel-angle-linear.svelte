<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/cihr55ejt.css';
import '../../css/s/sdb9eeb1p.css';
import '../../css/b/bkpaj_wfp.css';
import '../../css/p/pf95emypg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cihr55ejt"/><path class="sdb9eeb1p"/><path class="bkpaj_wfp"/><path class="pf95emypg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wheel-angle-linear" {...props}></Icon>
