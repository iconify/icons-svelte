<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpwog2bdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dpwog2bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:vending-machine-with-venus-mars" {...props}></Icon>
