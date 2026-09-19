<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pih7bsbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pih7bsbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spartan" {...props}></Icon>
