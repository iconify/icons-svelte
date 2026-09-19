<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko1t5iyft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ko1t5iyft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:venus-double" {...props}></Icon>
