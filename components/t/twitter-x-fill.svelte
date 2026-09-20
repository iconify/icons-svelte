<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrfvevb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rrfvevb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:twitter-x-fill" {...props}></Icon>
