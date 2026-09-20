<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx8zphbgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rx8zphbgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:social-pinterest-circular" {...props}></Icon>
