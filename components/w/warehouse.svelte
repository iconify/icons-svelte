<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avi9u4biy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="avi9u4biy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:warehouse" {...props}></Icon>
