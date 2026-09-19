<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sld3gxbqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sld3gxbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:unstable-orb" {...props}></Icon>
