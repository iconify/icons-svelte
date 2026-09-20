<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd3i1hf5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yd3i1hf5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:time-duration-off" {...props}></Icon>
