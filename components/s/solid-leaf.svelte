<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp2j0pbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yp2j0pbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:solid-leaf" {...props}></Icon>
