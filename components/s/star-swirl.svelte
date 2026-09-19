<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd-ed3c-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cd-ed3c-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:star-swirl" {...props}></Icon>
