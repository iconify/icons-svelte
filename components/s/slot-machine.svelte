<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4ipzwpsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h4ipzwpsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:slot-machine" {...props}></Icon>
