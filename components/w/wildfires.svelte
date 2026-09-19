<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf53ypbmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pf53ypbmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:wildfires" {...props}></Icon>
