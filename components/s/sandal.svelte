<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4zr8ab3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a4zr8ab3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sandal" {...props}></Icon>
