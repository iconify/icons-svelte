<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a840t8b4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a840t8b4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:turban" {...props}></Icon>
