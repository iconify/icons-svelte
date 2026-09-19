<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc0-x-b8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vc0-x-b8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:target-laser" {...props}></Icon>
