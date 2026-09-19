<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e67ynw8_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e67ynw8_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:surf-board" {...props}></Icon>
