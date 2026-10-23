<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr3rkb2_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rr3rkb2_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:square-dashed-mouse-pointer" {...props}></Icon>
