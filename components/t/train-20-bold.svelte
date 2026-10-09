<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whf-7i3fs.css';
import '../../css/m/mfifo7bbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="whf-7i3fs"/><path class="mfifo7bbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:train-20-bold" {...props}></Icon>
