<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc9txne7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kc9txne7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spine-arrow" {...props}></Icon>
