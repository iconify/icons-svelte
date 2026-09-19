<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tiog0gj8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tiog0gj8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:unfriendly-fire" {...props}></Icon>
