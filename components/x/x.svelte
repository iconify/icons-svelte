<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iey8yxkye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iey8yxkye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:x" {...props}></Icon>
