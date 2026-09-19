<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si_iur2zm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="si_iur2zm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:swipe-right-04" {...props}></Icon>
