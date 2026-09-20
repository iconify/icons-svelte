<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdh04ws8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="cdh04ws8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:travel-places-column-1-pillar-building-historical-column" {...props}></Icon>
