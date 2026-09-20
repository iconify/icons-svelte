<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/chjn_i6rt.css';
import '../../css/c/czv0ewbne.css';
import '../../css/g/g8k88bb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="chjn_i6rt"/><path class="czv0ewbne"/><path class="g8k88bb_r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:stars-minimalistic-bold" {...props}></Icon>
