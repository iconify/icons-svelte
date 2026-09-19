<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfksngbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tfksngbrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tyre" {...props}></Icon>
