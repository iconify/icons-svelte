<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auv0c3bkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="auv0c3bkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:shut-rose" {...props}></Icon>
