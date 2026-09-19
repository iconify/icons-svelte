<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv4k0-y3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gv4k0-y3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tree-roots" {...props}></Icon>
