<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp-ij2bmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bp-ij2bmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:wrapped-sweet" {...props}></Icon>
