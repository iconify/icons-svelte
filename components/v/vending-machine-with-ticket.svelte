<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv59zrbtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fv59zrbtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:vending-machine-with-ticket" {...props}></Icon>
