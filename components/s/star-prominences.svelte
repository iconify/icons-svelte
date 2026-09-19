<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu85-wv1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pu85-wv1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:star-prominences" {...props}></Icon>
