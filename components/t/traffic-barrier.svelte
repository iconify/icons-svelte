<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixr5g_bgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixr5g_bgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:traffic-barrier" {...props}></Icon>
