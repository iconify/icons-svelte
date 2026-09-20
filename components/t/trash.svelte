<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2u7ik9ps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="j2u7ik9ps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:trash" {...props}></Icon>
