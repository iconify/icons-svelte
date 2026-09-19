<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvjuc8mso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pvjuc8mso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:silver-bullet" {...props}></Icon>
