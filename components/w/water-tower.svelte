<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt7u62brp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vt7u62brp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:water-tower" {...props}></Icon>
