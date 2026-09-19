<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkewzlbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zkewzlbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:scan-outline" {...props}></Icon>
