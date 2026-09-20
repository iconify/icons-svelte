<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5468drzx.css';
import '../../css/z/zg9s_i7qh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e5468drzx"/><path clip-rule="evenodd" class="zg9s_i7qh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:shopping-store" {...props}></Icon>
