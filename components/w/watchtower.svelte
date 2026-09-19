<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i42fe6b8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i42fe6b8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:watchtower" {...props}></Icon>
