<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db2i566jf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="db2i566jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:vending-machine-with-cigarette-with-smoke-curl" {...props}></Icon>
