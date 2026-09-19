<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coaklgbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="coaklgbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tarot-01-the-magician" {...props}></Icon>
