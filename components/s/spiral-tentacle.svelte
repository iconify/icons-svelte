<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke4myvbye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ke4myvbye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spiral-tentacle" {...props}></Icon>
