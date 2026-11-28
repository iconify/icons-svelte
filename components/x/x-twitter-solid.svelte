<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/javx1rslg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="javx1rslg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:x-twitter-solid" {...props}></Icon>
