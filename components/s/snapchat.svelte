<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt_9i3bqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="rt_9i3bqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:snapchat" {...props}></Icon>
