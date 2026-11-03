<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqqcd7bya.css';
import '../../css/u/ul_bi8ihr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="hqqcd7bya"/><path class="ul_bi8ihr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:trident-emblem" {...props}></Icon>
