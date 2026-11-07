<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1h75hc1u.css';
import '../../css/l/lhcz5yp5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1h75hc1u"/><path clip-rule="evenodd" class="lhcz5yp5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:slider-vertical-minimalistic-bold-duotone" {...props}></Icon>
