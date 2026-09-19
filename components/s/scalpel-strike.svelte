<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqfbf6-1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cqfbf6-1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:scalpel-strike" {...props}></Icon>
