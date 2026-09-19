<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn4ielb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="mn4ielb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:smiley-fill-12" {...props}></Icon>
