<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-ns2xbva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k-ns2xbva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:travel-dress" {...props}></Icon>
