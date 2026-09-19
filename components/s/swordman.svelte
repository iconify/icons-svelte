<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7nd9-vlf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l7nd9-vlf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:swordman" {...props}></Icon>
