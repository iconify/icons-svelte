<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzuszhb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xzuszhb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:x" {...props}></Icon>
