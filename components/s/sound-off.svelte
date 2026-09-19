<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsnd0qbhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jsnd0qbhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sound-off" {...props}></Icon>
