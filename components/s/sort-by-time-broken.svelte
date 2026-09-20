<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/vkwwp42am.css';
import '../../css/b/bw4rmmbty.css';
import '../../css/n/nyyahnbxx.css';
import '../../css/b/byu9zgdxu.css';
import '../../css/e/eonjggvry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vkwwp42am"/><path class="bw4rmmbty"/><path class="nyyahnbxx"/><circle class="byu9zgdxu"/><path class="eonjggvry"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sort-by-time-broken" {...props}></Icon>
