<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzu3_9bar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="hzu3_9bar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:truck-medical" {...props}></Icon>
