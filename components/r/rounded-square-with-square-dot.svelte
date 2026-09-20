<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxhg82bqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xxhg82bqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rounded-square-with-square-dot" {...props}></Icon>
