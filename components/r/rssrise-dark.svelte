<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq7ek5b7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rq7ek5b7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rssrise-dark" {...props}></Icon>
