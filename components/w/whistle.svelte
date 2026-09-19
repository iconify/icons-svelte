<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmxh44brd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tmxh44brd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:whistle" {...props}></Icon>
