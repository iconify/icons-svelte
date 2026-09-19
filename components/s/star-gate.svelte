<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bg_e5np9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bg_e5np9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:star-gate" {...props}></Icon>
