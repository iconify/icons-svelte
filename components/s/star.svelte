<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu42j5gbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":778,"height":739};
const content = `<path class="yu42j5gbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:star" {...props}></Icon>
