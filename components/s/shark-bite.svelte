<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwk70sbgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qwk70sbgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:shark-bite" {...props}></Icon>
