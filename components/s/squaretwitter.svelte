<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wia0a812e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="wia0a812e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squaretwitter" {...props}></Icon>
