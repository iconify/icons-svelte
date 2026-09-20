<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owfdg3b6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="owfdg3b6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:shopping-box" {...props}></Icon>
