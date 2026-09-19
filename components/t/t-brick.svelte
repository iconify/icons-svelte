<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj7h58bge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nj7h58bge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:t-brick" {...props}></Icon>
