<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxma8lbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="uxma8lbox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:six-of-characters-mahjong" {...props}></Icon>
