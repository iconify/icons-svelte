<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0ar6obby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="j0ar6obby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:subscript" {...props}></Icon>
