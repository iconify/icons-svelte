<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxw6qj_ik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxw6qj_ik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-star-line" {...props}></Icon>
