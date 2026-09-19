<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmiv46s4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tmiv46s4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:three-pointed-shuriken" {...props}></Icon>
