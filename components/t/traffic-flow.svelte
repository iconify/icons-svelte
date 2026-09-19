<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep-7nhd8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ep-7nhd8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:traffic-flow" {...props}></Icon>
