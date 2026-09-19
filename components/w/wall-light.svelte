<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb5vehukz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gb5vehukz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:wall-light" {...props}></Icon>
