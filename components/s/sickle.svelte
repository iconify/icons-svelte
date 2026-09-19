<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2th5c_1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j2th5c_1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sickle" {...props}></Icon>
