<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfecfcb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rfecfcb4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:stigmata" {...props}></Icon>
