<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgtd15b3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgtd15b3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:watering-pot-outline" {...props}></Icon>
