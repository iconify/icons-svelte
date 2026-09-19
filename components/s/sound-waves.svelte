<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwah2gwwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kwah2gwwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sound-waves" {...props}></Icon>
