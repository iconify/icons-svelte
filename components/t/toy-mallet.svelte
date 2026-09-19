<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yti0hccuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yti0hccuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:toy-mallet" {...props}></Icon>
