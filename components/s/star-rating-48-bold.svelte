<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgjq70q0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rgjq70q0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:star-rating-48-bold" {...props}></Icon>
