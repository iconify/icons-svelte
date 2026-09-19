<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds1i_q67m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ds1i_q67m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:worried-eyes" {...props}></Icon>
