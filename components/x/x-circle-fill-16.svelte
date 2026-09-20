<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_f48ibsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t_f48ibsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:x-circle-fill-16" {...props}></Icon>
