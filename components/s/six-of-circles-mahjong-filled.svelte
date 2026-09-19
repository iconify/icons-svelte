<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6imtiaxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="j6imtiaxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:six-of-circles-mahjong-filled" {...props}></Icon>
