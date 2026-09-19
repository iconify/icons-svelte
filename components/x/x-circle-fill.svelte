<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6e0m7bry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w6e0m7bry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:x-circle-fill" {...props}></Icon>
