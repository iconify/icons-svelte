<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps73hmllh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ps73hmllh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:temporary-shield" {...props}></Icon>
