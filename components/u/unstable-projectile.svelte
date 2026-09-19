<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mal-u0bsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mal-u0bsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:unstable-projectile" {...props}></Icon>
