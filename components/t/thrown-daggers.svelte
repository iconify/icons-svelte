<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unkg-0nfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="unkg-0nfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:thrown-daggers" {...props}></Icon>
