<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqzy1o9tj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iqzy1o9tj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:steampunk-goggles" {...props}></Icon>
