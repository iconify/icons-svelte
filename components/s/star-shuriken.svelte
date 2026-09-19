<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8gj4dbhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i8gj4dbhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:star-shuriken" {...props}></Icon>
