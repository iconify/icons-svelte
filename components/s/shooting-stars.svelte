<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2uq_9q7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p2uq_9q7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shooting-stars" {...props}></Icon>
