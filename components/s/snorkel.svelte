<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il6k9zb_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="il6k9zb_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:snorkel" {...props}></Icon>
