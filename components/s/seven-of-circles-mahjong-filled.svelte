<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukk5zubmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ukk5zubmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:seven-of-circles-mahjong-filled" {...props}></Icon>
