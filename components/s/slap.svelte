<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4p4-82my.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q4p4-82my"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:slap" {...props}></Icon>
