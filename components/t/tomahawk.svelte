<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhu81yb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xhu81yb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tomahawk" {...props}></Icon>
