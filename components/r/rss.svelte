<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlia8ab3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1408};
const content = `<path class="jlia8ab3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:rss" {...props}></Icon>
