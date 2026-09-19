<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_l3c90rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r_l3c90rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ship-wheel" {...props}></Icon>
