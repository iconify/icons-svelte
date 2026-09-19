<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj-4mebdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pj-4mebdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:wrecking-ball" {...props}></Icon>
