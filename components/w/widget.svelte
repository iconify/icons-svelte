<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0kf1zuso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0kf1zuso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:widget" {...props}></Icon>
