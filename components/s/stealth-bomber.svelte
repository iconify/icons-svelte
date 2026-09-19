<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdkq10bvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wdkq10bvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:stealth-bomber" {...props}></Icon>
