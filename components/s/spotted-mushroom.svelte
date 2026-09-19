<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftfqew1zn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ftfqew1zn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spotted-mushroom" {...props}></Icon>
