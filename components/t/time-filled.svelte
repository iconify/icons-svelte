<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/faoq3ykkk.css';
import '../../css/d/d28ipjbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="faoq3ykkk"/><path class="d28ipjbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:time-filled" {...props}></Icon>
