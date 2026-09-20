<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j801xucsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j801xucsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:twitter-retweet" {...props}></Icon>
