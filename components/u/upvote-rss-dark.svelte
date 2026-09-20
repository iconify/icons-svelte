<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxtgz5blq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oxtgz5blq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:upvote-rss-dark" {...props}></Icon>
