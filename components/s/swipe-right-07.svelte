<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se3kvac6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="se3kvac6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:swipe-right-07" {...props}></Icon>
