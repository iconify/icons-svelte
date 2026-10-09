<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuzmv1qpb.css';
import '../../css/p/p_zjrxi1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nuzmv1qpb"/><path class="p_zjrxi1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-speed-20-bold" {...props}></Icon>
