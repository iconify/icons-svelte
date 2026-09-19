<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en3yd4b4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1728,"height":1408};
const content = `<path class="en3yd4b4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:truck" {...props}></Icon>
