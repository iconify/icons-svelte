<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkyw1x0bs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nkyw1x0bs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:south-africa-flag" {...props}></Icon>
