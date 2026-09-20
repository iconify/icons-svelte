<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc77rmbbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jc77rmbbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:zoom-in-line" {...props}></Icon>
