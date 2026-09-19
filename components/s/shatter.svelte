<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9j4j5ave.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c9j4j5ave"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:shatter" {...props}></Icon>
