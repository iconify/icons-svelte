<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsmq2s_xp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bsmq2s_xp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:slippers" {...props}></Icon>
