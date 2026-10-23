<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmu9v49lr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kmu9v49lr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:streaming-embedded" {...props}></Icon>
