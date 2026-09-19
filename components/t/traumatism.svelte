<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/ch1v3-bgw.css';
import '../../css/a/aev7hacfv.css';
import '../../css/k/kue5013mz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="ch1v3-bgw"/><path class="aev7hacfv"/><path class="kue5013mz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:traumatism" {...props}></Icon>
