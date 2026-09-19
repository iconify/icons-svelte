<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxe0aobvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kxe0aobvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:static" {...props}></Icon>
