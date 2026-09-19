<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb2fnotud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jb2fnotud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:visored-helm" {...props}></Icon>
