<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/q/qaaztzdak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":240,"height":28};
const content = `<defs><filter id="SVG70vUqbqX"><feColorMatrix in="SourceGraphic" values="0 0 0 0 1.000000 0 0 0 0 1.000000 0 0 0 0 1.000000 0 0 0 1.000000 0"/></filter></defs><g filter="url(#SVG70vUqbqX)" transform="translate(-134 -25)" class="bi12bsetm"><path class="qaaztzdak"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:voicemod-dark" {...props}></Icon>
