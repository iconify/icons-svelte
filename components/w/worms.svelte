<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krumpib3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="krumpib3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:worms" {...props}></Icon>
