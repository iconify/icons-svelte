<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilr3y11pt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ilr3y11pt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:team-upgrade" {...props}></Icon>
