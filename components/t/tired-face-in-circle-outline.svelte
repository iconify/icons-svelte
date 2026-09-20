<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c79_y39oy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c79_y39oy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tired-face-in-circle-outline" {...props}></Icon>
