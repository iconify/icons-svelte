<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbe7n819p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="tbe7n819p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:stopwatch-20" {...props}></Icon>
