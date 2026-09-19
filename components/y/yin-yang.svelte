<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuq0kccjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yuq0kccjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:yin-yang" {...props}></Icon>
