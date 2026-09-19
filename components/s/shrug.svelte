<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le3c-acut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="le3c-acut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:shrug" {...props}></Icon>
