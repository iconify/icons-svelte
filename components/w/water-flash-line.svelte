<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti9baybtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ti9baybtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:water-flash-line" {...props}></Icon>
