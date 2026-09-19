<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oia5jetrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oia5jetrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sharp-shuriken" {...props}></Icon>
