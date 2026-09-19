<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rupycd98g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rupycd98g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:settings-knobs" {...props}></Icon>
