<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id1pz4b3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="id1pz4b3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:striped-sword" {...props}></Icon>
