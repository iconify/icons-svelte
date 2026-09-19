<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfk4xd31m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="wfk4xd31m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:twitter-stroke-12" {...props}></Icon>
