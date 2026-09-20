<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j83o6di_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j83o6di_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:slice-of-pan-bread" {...props}></Icon>
