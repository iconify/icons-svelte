<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypb-jhynf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ypb-jhynf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ship-2-line" {...props}></Icon>
