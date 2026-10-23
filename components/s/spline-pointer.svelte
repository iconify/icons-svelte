<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2f8oq7xh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2f8oq7xh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:spline-pointer" {...props}></Icon>
