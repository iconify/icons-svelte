<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9xszbbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t9xszbbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tourboat" {...props}></Icon>
