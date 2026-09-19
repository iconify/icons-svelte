<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2qm1ektf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d2qm1ektf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:static-waves" {...props}></Icon>
