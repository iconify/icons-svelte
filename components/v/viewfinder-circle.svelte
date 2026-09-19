<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxjkv33_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxjkv33_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:viewfinder-circle" {...props}></Icon>
