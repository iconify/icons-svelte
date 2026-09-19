<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbgpijh-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sbgpijh-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:suit-club-fill" {...props}></Icon>
