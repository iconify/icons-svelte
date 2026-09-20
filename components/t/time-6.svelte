<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-y6ppb6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="e-y6ppb6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:time-6" {...props}></Icon>
