<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgb51vb0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pgb51vb0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:trefoil-lily" {...props}></Icon>
