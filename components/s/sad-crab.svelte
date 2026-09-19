<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpgcizt_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lpgcizt_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sad-crab" {...props}></Icon>
