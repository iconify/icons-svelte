<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i16vfccsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i16vfccsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:six-eyes" {...props}></Icon>
