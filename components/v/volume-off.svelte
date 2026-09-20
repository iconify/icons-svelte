<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di-rr7o5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="di-rr7o5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:volume-off" {...props}></Icon>
