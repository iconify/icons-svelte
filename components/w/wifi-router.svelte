<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5080z4re.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q5080z4re"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:wifi-router" {...props}></Icon>
