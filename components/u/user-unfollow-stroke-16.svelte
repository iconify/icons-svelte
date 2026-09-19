<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwd-2zbgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lwd-2zbgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:user-unfollow-stroke-16" {...props}></Icon>
