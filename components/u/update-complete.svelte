<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6e31r93c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r6e31r93c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:update-complete" {...props}></Icon>
