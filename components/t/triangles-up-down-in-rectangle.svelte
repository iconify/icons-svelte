<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqlkubb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rqlkubb-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:triangles-up-down-in-rectangle" {...props}></Icon>
