<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en1hy5blk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="en1hy5blk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:tablet-selected" {...props}></Icon>
