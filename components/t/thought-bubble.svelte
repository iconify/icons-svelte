<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl1dj3b2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kl1dj3b2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:thought-bubble" {...props}></Icon>
