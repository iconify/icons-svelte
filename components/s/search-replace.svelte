<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfkpbtgle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":376,"height":400};
const content = `<path class="qfkpbtgle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:search-replace" {...props}></Icon>
