<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8t3jxb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f8t3jxb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:vending-machine-with-postage-stamp" {...props}></Icon>
