<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrrpgk59a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lrrpgk59a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spinning-ribbons" {...props}></Icon>
