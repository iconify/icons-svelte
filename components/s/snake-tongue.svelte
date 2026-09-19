<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-1y49bzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r-1y49bzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:snake-tongue" {...props}></Icon>
