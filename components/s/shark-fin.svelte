<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3p9lioqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c3p9lioqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:shark-fin" {...props}></Icon>
