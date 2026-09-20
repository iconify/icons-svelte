<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdoj5cb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mdoj5cb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:tower-communication" {...props}></Icon>
