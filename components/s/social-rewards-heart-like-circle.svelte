<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag2g7gv9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ag2g7gv9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:social-rewards-heart-like-circle" {...props}></Icon>
