<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jruk4-ytp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jruk4-ytp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:turtle-shell" {...props}></Icon>
