<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp8jjlbzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lp8jjlbzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:triangle-right-with-plus" {...props}></Icon>
