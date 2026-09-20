<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dodmv35as.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dodmv35as"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:video-off" {...props}></Icon>
