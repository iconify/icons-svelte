<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/rk-y7ubcm.css';
import '../../css/k/k012t9-gu.css';
import '../../css/e/euee9wbaf.css';
import '../../css/y/ytznpnb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="rk-y7ubcm"/><path class="k012t9-gu wm-a"/><path class="euee9wbaf wm-a"/><path class="ytznpnb1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shopping-cart-duo" {...props}></Icon>
