<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c99w-65vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="c99w-65vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:seven-of-circles-mahjong" {...props}></Icon>
