<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i336q6bsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i336q6bsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:voodoo-doll" {...props}></Icon>
