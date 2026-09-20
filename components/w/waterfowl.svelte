<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfg9cb5pf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pfg9cb5pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:waterfowl" {...props}></Icon>
