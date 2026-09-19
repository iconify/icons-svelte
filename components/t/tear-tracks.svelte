<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-d83hgrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s-d83hgrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tear-tracks" {...props}></Icon>
