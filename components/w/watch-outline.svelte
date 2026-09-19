<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_9832jzs.css';
import '../../css/s/s5cgq7bny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="d_9832jzs"/><path class="s5cgq7bny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:watch-outline" {...props}></Icon>
