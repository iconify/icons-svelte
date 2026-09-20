<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k97f4fb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k97f4fb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:translate-outline" {...props}></Icon>
