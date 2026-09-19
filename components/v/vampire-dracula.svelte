<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snixmfrdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="snixmfrdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:vampire-dracula" {...props}></Icon>
