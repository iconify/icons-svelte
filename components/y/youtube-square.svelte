<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4oogcjvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="w4oogcjvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:youtube-square" {...props}></Icon>
