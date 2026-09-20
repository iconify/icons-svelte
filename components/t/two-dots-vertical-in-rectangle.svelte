<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgso04boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cgso04boy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:two-dots-vertical-in-rectangle" {...props}></Icon>
