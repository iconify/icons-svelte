<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v62n5nbef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v62n5nbef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sonic-shout" {...props}></Icon>
