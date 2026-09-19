<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6mn8tkpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r6mn8tkpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sauropod-skeleton" {...props}></Icon>
