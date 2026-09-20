<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8j5efbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8j5efbwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:subreddit-line" {...props}></Icon>
