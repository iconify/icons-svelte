<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v83gpgbwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v83gpgbwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:soldering-iron" {...props}></Icon>
