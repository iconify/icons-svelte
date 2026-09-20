<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7d6a-bpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7d6a-bpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:social-twitter-circular" {...props}></Icon>
