<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzkwmo0ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gzkwmo0ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tire-iron" {...props}></Icon>
