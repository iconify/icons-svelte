<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2wj4l62v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p2wj4l62v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:volleyball-ball" {...props}></Icon>
