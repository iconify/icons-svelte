<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro9gsfbig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ro9gsfbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:vending-machine-with-greek-cross" {...props}></Icon>
