<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/yvsdj-byp.css';
import '../../css/b/bybz0tjxq.css';
import '../../css/n/nj1ev_b1z.css';
import '../../css/f/fvpfrkbjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="yvsdj-byp"/><path class="bybz0tjxq"/><path class="nj1ev_b1z"/><path class="fvpfrkbjr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:server-off" {...props}></Icon>
