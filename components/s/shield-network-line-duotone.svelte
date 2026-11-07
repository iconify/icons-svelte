<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/noff7ob6h.css';
import '../../css/r/r5fahkzon.css';
import '../../css/k/koiq71blg.css';
import '../../css/t/tokx6ighc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="noff7ob6h"/><path class="r5fahkzon"/><path class="koiq71blg"/><path class="tokx6ighc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shield-network-line-duotone" {...props}></Icon>
