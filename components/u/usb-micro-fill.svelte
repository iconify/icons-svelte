<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1yn72bqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b1yn72bqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:usb-micro-fill" {...props}></Icon>
