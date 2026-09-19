<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no5sv1bvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="no5sv1bvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:winchester-rifle" {...props}></Icon>
