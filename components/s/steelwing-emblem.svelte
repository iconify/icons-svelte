<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6gj51ubz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o6gj51ubz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:steelwing-emblem" {...props}></Icon>
