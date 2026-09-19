<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnas29efh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nnas29efh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:trefoil-shuriken" {...props}></Icon>
