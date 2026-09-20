<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db4qkfb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="db4qkfb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:sync" {...props}></Icon>
