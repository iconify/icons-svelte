<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8m9zlofw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x8m9zlofw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:triangle-right-outline" {...props}></Icon>
