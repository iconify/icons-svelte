<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/ndq7bz-2p.css';
import '../../css/e/e8y4q8brq.css';
import '../../css/k/k1uq304yb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="ndq7bz-2p"/><rect class="e8y4q8brq"/><circle transform="matrix(0 -1 -1 0 30 24)" class="k1uq304yb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:wallet-three" {...props}></Icon>
