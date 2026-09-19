<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqu_v-bil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vqu_v-bil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:suckered-tentacle" {...props}></Icon>
