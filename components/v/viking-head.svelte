<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5bya897a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m5bya897a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:viking-head" {...props}></Icon>
