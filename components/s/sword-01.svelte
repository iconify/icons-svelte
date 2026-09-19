<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/k/k3g88ac1q.css';
import '../../css/n/nf31t0akt.css';
import '../../css/v/vco_ahbxh.css';
import '../../css/i/i9gyr2bxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="k3g88ac1q"/><path class="nf31t0akt"/><path class="vco_ahbxh"/><path class="i9gyr2bxw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sword-01" {...props}></Icon>
