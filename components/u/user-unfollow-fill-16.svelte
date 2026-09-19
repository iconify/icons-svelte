<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1k04xebr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r1k04xebr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:user-unfollow-fill-16" {...props}></Icon>
