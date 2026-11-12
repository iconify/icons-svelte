<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt4l2gbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jt4l2gbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tasmocompiler-dark" {...props}></Icon>
