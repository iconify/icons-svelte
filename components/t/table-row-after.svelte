<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozn60lppr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ozn60lppr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:table-row-after" {...props}></Icon>
