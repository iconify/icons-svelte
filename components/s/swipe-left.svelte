<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5_u22bhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p5_u22bhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:swipe-left" {...props}></Icon>
