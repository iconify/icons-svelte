<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh27wbbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uh27wbbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tornado-20-bold" {...props}></Icon>
