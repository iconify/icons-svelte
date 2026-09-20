<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7yq7ybul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p7yq7ybul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:wood" {...props}></Icon>
