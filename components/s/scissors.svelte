<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs2z8bzes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zs2z8bzes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:scissors" {...props}></Icon>
