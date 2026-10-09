<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnkuq4b8x.css';
import '../../css/t/tz4q3ccfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cnkuq4b8x"/><path class="tz4q3ccfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:toaster-20-bold" {...props}></Icon>
