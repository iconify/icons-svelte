<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-00757da.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v-00757da"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:three-leaves" {...props}></Icon>
