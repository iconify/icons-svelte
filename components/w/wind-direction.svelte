<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3rpqtqvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1537,"height":1537};
const content = `<path class="k3rpqtqvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:wind-direction" {...props}></Icon>
