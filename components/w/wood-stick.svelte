<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw1xjyb6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bw1xjyb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:wood-stick" {...props}></Icon>
