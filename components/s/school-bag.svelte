<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_t0vpb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u_t0vpb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:school-bag" {...props}></Icon>
