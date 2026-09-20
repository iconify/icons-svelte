<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8pyclbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p8pyclbov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yelp" {...props}></Icon>
