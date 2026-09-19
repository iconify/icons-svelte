<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7k4t3bue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r7k4t3bue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tornado-discs" {...props}></Icon>
