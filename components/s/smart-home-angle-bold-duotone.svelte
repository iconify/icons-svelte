<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cznruvbvt.css';
import '../../css/l/la8zw0-un.css';
import '../../css/r/rtss7cadq.css';
import '../../css/y/y37_nkb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cznruvbvt"/><path class="la8zw0-un"/><path class="rtss7cadq"/><path class="y37_nkb_p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smart-home-angle-bold-duotone" {...props}></Icon>
