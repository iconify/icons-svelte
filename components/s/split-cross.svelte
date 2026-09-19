<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tphb67bhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tphb67bhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:split-cross" {...props}></Icon>
