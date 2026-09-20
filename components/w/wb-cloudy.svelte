<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je79ww9ik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="je79ww9ik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wb-cloudy" {...props}></Icon>
