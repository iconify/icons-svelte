<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veh0-ibhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="veh0-ibhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:subtract-1-remix" {...props}></Icon>
