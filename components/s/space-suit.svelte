<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vobx_nbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vobx_nbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:space-suit" {...props}></Icon>
