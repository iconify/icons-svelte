<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/its__g-kj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="its__g-kj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:view-list" {...props}></Icon>
