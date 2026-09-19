<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps048zbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ps048zbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:rubber-boot" {...props}></Icon>
