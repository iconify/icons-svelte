<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d94-lnnrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d94-lnnrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:winged-shield" {...props}></Icon>
