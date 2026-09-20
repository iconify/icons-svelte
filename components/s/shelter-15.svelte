<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6h-xxbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x6h-xxbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:shelter-15" {...props}></Icon>
