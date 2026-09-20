<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/frvs39b5t.css';
import '../../css/k/k5ikzyb2n.css';
import '../../css/b/bv162rb1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="frvs39b5t"/><path class="k5ikzyb2n"/><path class="bv162rb1m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:traffic-economy-outline" {...props}></Icon>
