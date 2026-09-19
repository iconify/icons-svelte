<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afj6p5bbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="afj6p5bbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:stars-stack" {...props}></Icon>
