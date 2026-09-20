<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyjstn5af.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hyjstn5af"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:three-chevrons-right-above-conveyor-belt" {...props}></Icon>
