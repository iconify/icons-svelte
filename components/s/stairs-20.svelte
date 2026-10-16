<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1pq6-bwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x1pq6-bwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:stairs-20" {...props}></Icon>
