<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny-33twob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ny-33twob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tennis-racket" {...props}></Icon>
