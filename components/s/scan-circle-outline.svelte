<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsg5j7ibl.css';
import '../../css/v/vk92cd1sv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lsg5j7ibl"/><path class="vk92cd1sv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:scan-circle-outline" {...props}></Icon>
