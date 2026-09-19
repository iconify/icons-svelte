<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axg6-fbdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="axg6-fbdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:staircase-up" {...props}></Icon>
