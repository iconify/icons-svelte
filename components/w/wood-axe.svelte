<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okaev_bvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="okaev_bvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:wood-axe" {...props}></Icon>
