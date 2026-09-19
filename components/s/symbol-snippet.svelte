<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyw1c2bvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lyw1c2bvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:symbol-snippet" {...props}></Icon>
