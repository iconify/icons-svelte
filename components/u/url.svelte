<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8jnt9tue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q8jnt9tue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:url" {...props}></Icon>
