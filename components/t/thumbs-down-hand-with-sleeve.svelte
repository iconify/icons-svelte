<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt--_cb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kt--_cb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:thumbs-down-hand-with-sleeve" {...props}></Icon>
