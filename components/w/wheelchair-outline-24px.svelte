<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/iqvs1ctqv.css';
import '../../css/r/rqpnbwxgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="iqvs1ctqv"/><path clip-rule="evenodd" class="rqpnbwxgn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:wheelchair-outline-24px" {...props}></Icon>
