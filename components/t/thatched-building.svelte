<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0whlm67j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b0whlm67j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:thatched-building" {...props}></Icon>
