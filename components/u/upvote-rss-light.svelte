<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2k_pab-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u2k_pab-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:upvote-rss-light" {...props}></Icon>
