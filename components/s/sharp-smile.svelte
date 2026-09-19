<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8gl1j29h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y8gl1j29h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sharp-smile" {...props}></Icon>
