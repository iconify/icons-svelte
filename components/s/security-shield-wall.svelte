<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8eh7n5jh.css';
import '../../css/j/j7h15zsik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d8eh7n5jh"/><path class="j7h15zsik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:security-shield-wall" {...props}></Icon>
