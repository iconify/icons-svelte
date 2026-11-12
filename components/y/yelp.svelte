<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpvhud58c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xpvhud58c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yelp" {...props}></Icon>
