<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anza8ob-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="anza8ob-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:triangle-target" {...props}></Icon>
