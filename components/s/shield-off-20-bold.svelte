<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj2wnyv8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dj2wnyv8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shield-off-20-bold" {...props}></Icon>
