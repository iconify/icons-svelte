<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czaqnibmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="czaqnibmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:samus-helmet" {...props}></Icon>
