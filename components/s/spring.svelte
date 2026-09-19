<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dokfpeb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dokfpeb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spring" {...props}></Icon>
