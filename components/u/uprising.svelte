<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-fbg2v3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k-fbg2v3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:uprising" {...props}></Icon>
