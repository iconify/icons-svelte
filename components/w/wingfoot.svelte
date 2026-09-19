<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc6p9nboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zc6p9nboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:wingfoot" {...props}></Icon>
