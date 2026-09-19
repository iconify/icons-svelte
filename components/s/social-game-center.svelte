<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdgknib1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="pdgknib1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-game-center" {...props}></Icon>
