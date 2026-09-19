<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/q/qf6757bna.css';
import '../../css/b/bvdfp-bfv.css';
import '../../css/i/i9cp4bbah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="qf6757bna"/><circle class="bvdfp-bfv"/><path class="i9cp4bbah"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:send-limit-outline" {...props}></Icon>
