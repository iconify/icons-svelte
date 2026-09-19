<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdneszcxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":480};
const content = `<path class="bdneszcxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:smartphone-erase" {...props}></Icon>
