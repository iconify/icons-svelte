<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq8g_vbqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uq8g_vbqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sword-clash" {...props}></Icon>
