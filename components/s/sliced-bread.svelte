<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl5hcqbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pl5hcqbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sliced-bread" {...props}></Icon>
