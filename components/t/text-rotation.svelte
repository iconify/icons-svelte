<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa4crh6rn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="fa4crh6rn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:text-rotation" {...props}></Icon>
