<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2mtorz7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j2mtorz7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:wheelbarrow" {...props}></Icon>
