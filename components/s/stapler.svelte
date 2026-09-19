<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdhp95gbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qdhp95gbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:stapler" {...props}></Icon>
