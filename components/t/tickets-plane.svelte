<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/l/lpusqwbwb.css';
import '../../css/n/nagqqvblc.css';
import '../../css/n/nj4w60bmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lpusqwbwb"/><path class="nagqqvblc"/><path class="nj4w60bmc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tickets-plane" {...props}></Icon>
