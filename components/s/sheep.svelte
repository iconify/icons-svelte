<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk2-8rbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dk2-8rbie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sheep" {...props}></Icon>
