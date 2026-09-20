<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxgrxpsyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cxgrxpsyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wifi-no-signal-with-x" {...props}></Icon>
