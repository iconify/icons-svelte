<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4fl3t3ql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d4fl3t3ql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:stone-arrowhead-down" {...props}></Icon>
