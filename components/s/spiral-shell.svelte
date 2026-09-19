<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9n-k-bla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p9n-k-bla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spiral-shell" {...props}></Icon>
