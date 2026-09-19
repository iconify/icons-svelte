<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe2ker-yy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fe2ker-yy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spinning-wheel" {...props}></Icon>
