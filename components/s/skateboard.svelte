<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5jmkmbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s5jmkmbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:skateboard" {...props}></Icon>
