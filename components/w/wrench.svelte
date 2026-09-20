<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llj6lvbxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="llj6lvbxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:wrench" {...props}></Icon>
