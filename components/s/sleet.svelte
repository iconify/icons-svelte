<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rclnhcb_b.css';
import '../../css/z/z9u1ekeoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rclnhcb_b"/><path class="z9u1ekeoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:sleet" {...props}></Icon>
