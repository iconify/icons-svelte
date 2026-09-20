<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coowa9bje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="coowa9bje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:speech-bubble-quote-solid-expressive" {...props}></Icon>
