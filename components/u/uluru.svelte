<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3cbnzb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b3cbnzb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:uluru" {...props}></Icon>
