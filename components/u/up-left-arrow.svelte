<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7amu7_fh.css';
import '../../css/f/ftfoyqbcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="h7amu7_fh"/><path class="ftfoyqbcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:up-left-arrow" {...props}></Icon>
