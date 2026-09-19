<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdz8jibqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdz8jibqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:workflow" {...props}></Icon>
