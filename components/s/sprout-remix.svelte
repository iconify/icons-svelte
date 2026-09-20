<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip9qdkb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ip9qdkb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:sprout-remix" {...props}></Icon>
