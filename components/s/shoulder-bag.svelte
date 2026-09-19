<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emz1kui1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="emz1kui1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:shoulder-bag" {...props}></Icon>
