<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxvgxxkwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bxvgxxkwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:two-plus-over-water" {...props}></Icon>
