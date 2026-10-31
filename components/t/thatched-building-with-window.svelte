<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9im-ib6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j9im-ib6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:thatched-building-with-window" {...props}></Icon>
