<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7-sevcfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y7-sevcfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:sort-high-to-low-outline" {...props}></Icon>
