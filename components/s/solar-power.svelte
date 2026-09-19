<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smynt4b8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="smynt4b8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:solar-power" {...props}></Icon>
