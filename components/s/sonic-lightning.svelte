<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imh15rgco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="imh15rgco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sonic-lightning" {...props}></Icon>
