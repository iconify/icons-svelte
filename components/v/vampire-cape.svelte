<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9v0nvb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n9v0nvb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:vampire-cape" {...props}></Icon>
