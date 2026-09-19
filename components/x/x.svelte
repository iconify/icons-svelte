<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve2l6q1jt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ve2l6q1jt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:x" {...props}></Icon>
