<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2khq4k7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t2khq4k7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:wallet" {...props}></Icon>
