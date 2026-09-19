<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rojew6zkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rojew6zkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:seven-pointed-star" {...props}></Icon>
