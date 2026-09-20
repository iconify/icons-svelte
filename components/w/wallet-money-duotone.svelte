<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/x_811s6vd.css';
import '../../css/p/pyj541-1p.css';
import '../../css/q/qqnch-iej.css';
import '../../css/l/lx68tvzox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x_811s6vd"/><path clip-rule="evenodd" class="pyj541-1p"/><path class="qqnch-iej"/><path class="lx68tvzox"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:wallet-money-duotone" {...props}></Icon>
