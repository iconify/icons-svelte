<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8cyx9otq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8cyx9otq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:slideshow-4-line" {...props}></Icon>
