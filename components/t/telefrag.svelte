<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl6s_972s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tl6s_972s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:telefrag" {...props}></Icon>
