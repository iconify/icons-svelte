<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/ei2ht8bsv.css';
import '../../css/d/dp1n3q8en.css';
import '../../css/u/uv3cblu-e.css';
import '../../css/q/q8wvpccph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ei2ht8bsv"/><path class="dp1n3q8en"/><path class="uv3cblu-e"/><path class="q8wvpccph"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sd-card-bold-duotone" {...props}></Icon>
