<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjl8s6b6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mjl8s6b6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sink" {...props}></Icon>
