<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hog2xxb1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hog2xxb1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:scissors-coupon" {...props}></Icon>
