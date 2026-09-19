<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm48pi--i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rm48pi--i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:run-above" {...props}></Icon>
